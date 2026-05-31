# Flappy Disco

Flappy Bird sur une piste de danse — l'oiseau, c'est ta tête ; les tuyaux, des barres de pole dance.

## Jouer en local

1. Place ta photo (carrée idéalement, fond peu importe) à côté de `index.html` et nomme-la **`face.jpg`** (ou `face.png`).
2. Ouvre `index.html` dans un navigateur. C'est tout.

Sans photo, un avatar dessiné en SVG est utilisé à la place.

## Mettre en ligne sur GitHub Pages

```bash
git init
git add index.html face.jpg README.md
git commit -m "flappy disco"
git branch -M main
git remote add origin git@github.com:<ton-user>/flappy-disco.git
git push -u origin main
```

Puis dans le repo sur github.com : **Settings → Pages → Source = `Deploy from a branch` → Branch = `main` / `/ (root)`**. Au bout d'une minute, le jeu est en ligne sur `https://<ton-user>.github.io/flappy-disco/`.

Ouvre cette URL sur ton téléphone — tape l'écran pour faire battre des ailes.

## Contrôles

- Téléphone : tape l'écran
- Ordi : `Espace` ou `↑`

## Astuces

- Pour une meilleure tête : recadre ta photo en carré, centrée sur le visage, ~512×512px.
- Le meilleur score est enregistré en local (localStorage).
