# Consignes pour Claude

## Publication sur GitHub
- Ne jamais demander s'il faut pousser le code ou ouvrir une pull request.
- Après chaque modification : commit, push sur la branche de travail, puis ouvrir directement la pull request vers `main`.
- La seule étape laissée à l'utilisateur est la validation (fusion) de la pull request : lui donner le lien.

## Site
- Tout le site est dans `index.html` (fiches dans `matieres`, flashcards dans `flashcardsData`).
- Fiches en accordéon : grande partie → bouton flashcards de la partie puis titres des sous-parties → sous-partie : bouton flashcards en haut, puis blocs dépliables (notions, mécanismes, etc.).
- Origine d'une fiche : champ `classe` (`web`, `ia`, `humain`, `web-ia`, `ia-humain`, `web-humain`, `vide`).
- Apparence : le bloc « THÈME VISUEL » en fin de `<style>` regroupe les couleurs (variables `:root` / `body.night`) et les finitions.
