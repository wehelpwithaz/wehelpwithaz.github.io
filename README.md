# wehelpwithaz.github.io

Site développeur de **WeHelpWithAZ** (GitHub Pages) : https://wehelpwithaz.github.io

## Structure
| Chemin | Rôle |
|---|---|
| `index.html` | Accueil développeur : liste des applications |
| `privacy.html` | Principes de confidentialité communs à toutes les applications |
| `contact.html` | Contact et aide |
| `app-ads.txt` | Vérification AdMob, **un seul fichier pour toutes les applications** du compte pub-4725369225843007 |
| `assets/style.css` | Style partagé |
| `walletz/` | Pages de Walletz : présentation, `privacy.html`, `terms.html`, `support.html`, `promo.json` |

## Ajouter une application
1. Créer un dossier au nom court de l'application (ex. `focus-pomodoro/`) avec `index.html`, `privacy.html`, `terms.html`, `support.html`.
2. Ajouter sa carte dans `index.html`, sa ligne dans le tableau de `privacy.html` et son lien dans `contact.html`.
3. Dans Play Console, déclarer la politique `https://wehelpwithaz.github.io/<dossier>/privacy.html`
   et le site développeur `https://wehelpwithaz.github.io`.
4. Ne jamais modifier ni dupliquer `app-ads.txt` : il couvre déjà toutes les applications.

## Codes promo Walletz
`walletz/promo.json` contient uniquement des empreintes SHA-256. Il est mis à jour avec
`tools/New-WalletzCode.ps1` et `tools/Disable-WalletzCode.ps1` (projet Walletz), puis publié ici.
