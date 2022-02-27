![Booki logo](assets/images/booki.png)

> Projet n°2 OpenClassrooms Développeur Web. — 27 février 2022.

## Spécifications fonctionnelles

- Les usagers pourront rechercher des hébergements dans la ville de
leur choix. Le champ de recherche est **un champ de saisie**, le texte
doit donc pouvoir être édité par l’utilisateur. **Il faut englober ce
champ dans un formulaire pour que ce dernier soit valide auprès du
W3C**. La partie recherche ne doit pas être fonctionnelle.
- Chaque **carte d’hébergement ou d’activité devra être cliquable** dans
son intégralité (pas uniquement le titre). Pour l’instant, les liens sont
vides. On peut utiliser un attribut `href=”#”` pour simuler la
présence d’un lien.
- Les **filtres doivent changer d’apparence au survol**. Je te laisse décider
de l’effet approprié, je n’ai pas encore eu le temps de me pencher
dessus. Par contre, ils ne doivent pas être fonctionnels.
- Les textes **“Hébergements” et “Activités”**, situés dans l’en-tête, sont
**des liens**. Ils doivent mener **respectivement vers la section
“Hébergements à Marseille” et “Activités à Marseille”**.


## Cahier des charges

- Responsive design
- Breakpoints : **992px** (écrans d'ordinateurs), **768px** (tablettes) & **>768px** (smartphones)
- Desktop first
- Adapter le format image → Compresser les images & optimiser la qualité sous format `.webp`
- Icônes : Font Awesome → **[Fork Awesome](https://forkaweso.me/Fork-Awesome/icons/)** (plus léger)
- Intégrer les couleurs, tel le bleu, bleu clair et le gris.
- Font : **[Raleway](https://fonts.google.com/specimen/Raleway)** 
- Basé sur du **Flexbox**
- Balises sémantiques
- Conforme aux **normes W3C**
- Aucun framework CSS
- Aucun préprocesseur CSS

## Palette des couleurs

- `#0065FC` → **primary-color** (bleu)
- `#DEEBFF` → **primary-color-light** (bleu clair)
- `#F2F2F2` → **grey** (gris)

## Développement

- Projet réalisé avec **Intellij**. 
- Images compressées et transformé en format adéquat avec **[Squoosh](https://squoosh.app/)**

## Notes

Le font family **Raleway** est distribué depuis le local et non venant du CDN de Google.
Le dossier se trouve dans [assets/fonts](assets/fonts).

## Licences

Fork Awesome V1.2.0 — [SIL OFL 1.1](https://forkaweso.me/Fork-Awesome/license/)

____

Code versionné sur GitHub pour plus de simplicité.
