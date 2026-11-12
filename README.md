# PM Training

Application de coaching PM Training, installable sur téléphone : zones d'entraînement (course, cardio, vélo, natation), calculateur de position vélo, offres de coaching et retours d'athlètes.

## Installer l'app

Ouvrir https://menardpa-design.github.io/pm-training-app/ sur le téléphone, puis :
- iPhone (Safari) : Partager → « Sur l'écran d'accueil » ;
- Android (Chrome) : menu ⋮ → « Installer l'application ».

## Modifier les contenus

Tout est dans `index.html` : les offres dans la section `id="offres"`, les témoignages dans la liste `TESTIMONIALS` du script. Après une modification, changer `CACHE` dans `sw.js` (ex. `pm-training-v2`) pour que les téléphones récupèrent la nouvelle version.
