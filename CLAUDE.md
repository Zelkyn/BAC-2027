# Consignes pour Claude

## Publication sur GitHub
- Ne jamais demander s'il faut pousser le code ou ouvrir une pull request.
- Après chaque modification : commit, push sur la branche de travail, puis ouvrir directement la pull request vers `main`.
- La seule étape laissée à l'utilisateur est la validation (fusion) de la pull request : lui donner le lien.

## Site
- Tout le site est dans `index.html` (fiches dans `matieres`, flashcards dans `flashcardsData`).
- Fiches en accordéon : grande partie → bouton flashcards de la partie puis titres des sous-parties → sous-partie : bouton flashcards en haut, puis blocs dépliables (notions, mécanismes, etc.).
- Origine d'une fiche : champ `classe` = `web` (bleu), `ia` (violet), `eleve` (vert), `enseignant` (jaune), ou deux combinées dans cet ordre (`web-ia`, `web-eleve`, `web-enseignant`, `ia-eleve`, `ia-enseignant`, `eleve-enseignant`) ; `vide` si non renseignée. L'origine « humaine » n'existe plus.
- Listes de fiches : intitulés officiels des programmes de terminale (BO 2019, en vigueur pour le bac 2027), dans l'ordre du programme. Les fiches de méthodologie sont toujours placées en dernier.
- Apparence : le bloc « THÈME VISUEL » en fin de `<style>` regroupe les couleurs (variables `:root` / `body.night`) et les finitions.
