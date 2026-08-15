# 3 ans

Petit site mobile à faire défiler (flèches ou swipe), une carte par écran.

## Modifier le contenu

Tout se passe dans `index.html`, dans le bloc `SLIDES` en haut du `<script>`.
Chaque élément du tableau est une carte : `badge`, `title`, `text`, `emoji`.

Pour mettre une vraie photo à la place d'un emoji :
1. Dépose ton image dans le dossier `images/` (ex: `images/magellan.jpg`)
2. Dans `SLIDES`, remplace `image: null` par `image: "images/magellan.jpg"`

## Voir le résultat

Ouvre simplement `index.html` dans un navigateur (double-clic dessus),
ou en local : `python3 -m http.server` puis va sur `http://localhost:8000`.

## Partager le lien (GitHub Pages)

1. Sur GitHub : **Settings → Pages**
2. Source : *Deploy from a branch*, branche `main`, dossier `/ (root)`
3. Après ~1 minute, le lien sera `https://zamasubl4ck.github.io/Avcdelachance2/`

Il ne reste plus qu'à envoyer ce lien.
