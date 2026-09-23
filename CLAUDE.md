# Consignes pour Claude

## Publication sur GitHub
- Ne jamais demander s'il faut pousser le code ou ouvrir une pull request.
- Après chaque modification : commit, push sur la branche de travail, puis ouvrir directement la pull request vers `main`.
- La seule étape laissée à l'utilisateur est la validation (fusion) de la pull request : lui donner le lien.

## Site
- Tout le site est dans `index.html` (fiches dans `matieres`, flashcards dans `flashcardsData`).
- Fiches en accordéon : grande partie → sous-parties (+ bouton flashcards de la partie) → sous-partie : bouton flashcards en haut, puis blocs dépliables (notions, mécanismes, etc.).
- Origine d'une fiche : champ `classe` (`web`, `ia`, `humain`, `web-ia`…). Pour masquer temporairement couleurs et noms d'origine : `ORIGINES_DESACTIVEES = true`.
