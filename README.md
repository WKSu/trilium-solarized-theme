# Trilium Solarized Theme
A [solarized](https://ethanschoonover.com/solarized/) theme for the notetaking app [Trilium](https://github.com/zadam/trilium).

![image](https://user-images.githubusercontent.com/49348667/111087638-050cb300-8523-11eb-819a-ca768fd0948a.png)


## Installation
- Copy the contents of the `solarized.css` file into a Trilium note.
- Change the type of the note to CSS.
- Add the label `#appTheme=solarized`
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
