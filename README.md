# radiopink — Mon Mariage · Radio 📻

Radio 3D interactive du Jour J : **animatrice avec une vraie voix enregistrée**, direct calé sur l'éditeur de timeline, playlist musicale intégrable et scripts générés par **DeepSeek**.

## Lancer la radio

```bash
python3 -m http.server 8000
# puis ouvrir http://localhost:8000
```

> Un serveur local est nécessaire pour que le moteur Web Audio analyse la voix et la musique (l'ouverture directe du fichier en double-clic peut couper la synchro labiale).

## ● En Direct — le cœur de la radio

- **● En Direct** (ou `Espace`, ou le gros bouton ▶ sur la radio 3D) : jingle d'ouverture → **Léa présente chaque moment du Jour J** → musique entre deux moments → transitions dédicaces → générique de fin.
- L'horloge virtuelle de la journée avance (vitesse **×24 / ×48 / ×120** dans le panneau Timeline) : le curseur de la timeline, l'écran LCD et le bandeau « En direct » suivent le moment en cours en temps réel.
- **▶ sur n'importe quel moment** (dans la liste ou sur le bandeau de la timeline) : Léa en parle immédiatement à l'antenne, même hors direct.
- **Sous-titres** en direct en bas d'écran + **synchro labiale** : la bouche de l'animatrice 3D et du portrait LCD bougent avec la vraie voix (analyse Web Audio).
- Quand Léa parle, la musique s'abaisse automatiquement (ducking), comme sur une vraie radio.

## Timeline · Jour J

Horaires, titres, durées et couleurs **modifiables en direct** — l'affichage des trois radios, le programme du direct et les interventions de Léa s'adaptent instantanément. Presets **Classique / Intime / Festif**. Léa reconnaît le type de chaque moment (cérémonie, cocktail, dîner, ouverture de bal, DJ…) via ses titres.

## Playlist · Musiques

Ajoutez vos titres (**＋ Ajouter** ou **glisser-déposer** MP3/M4A/WAV/OGG) : ils passent à l'antenne entre les interventions de Léa, en boucle. Réordonnez, supprimez, passez en lecture seule. Playlist vide ? La **session synthé « Néo-Romantique »** intégrée assure la musique. Tout est lu **en local**, rien n'est envoyé sur Internet.

## ✨ DeepSeek · Animatrice

Dans le panneau DeepSeek : collez votre **clé API DeepSeek** (sk-…, stockée uniquement dans votre navigateur), renseignez prénoms / date / lieu, puis **Générer les scripts du jour J** : DeepSeek rédige une intervention personnalisée pour chaque moment (titres modifiés compris), lue à l'antenne avec sous-titres. Le bouton ✨ d'une ligne régénère le script d'un seul moment.

## Voix de Léa

Les interventions standard sont des **vraies voix humaines pré-enregistrées** (`audio/lea/*.mp3`), pas de la synthèse robotique. Les scripts ✨ DeepSeek personnalisés sont lus par la meilleure voix française disponible dans le navigateur.

## Raccourcis

`Espace` direct · `M` musique · `T` timeline · `P` playlist · `D` DeepSeek · molette zoom · drag orbite
