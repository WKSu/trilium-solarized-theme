# Trilium Solarized Theme
A [solarized](https://ethanschoonover.com/solarized/) theme for the notetaking app [Trilium](https://github.com/zadam/trilium).

![image](https://user-images.githubusercontent.com/49348667/139704221-5f90f145-a272-4b34-9f8e-be2d41e30630.png)


## Installation
- Copy the contents of the `solarized.css` file into a Trilium note.
- Change the type of the note to CSS.
- Add the label `#appTheme=solarized-light` (or `dark`)
- Go to options and select this theme 🥳

`solarized.css` applies either the dark or light theme based on a media query.

## Updating the repo

Install sass:

```bash
sudo npm install -g sass
```

After changes, rebuild `solarized.css`:

```bash
sass --no-source-map solarized.scss solarized.css
```
