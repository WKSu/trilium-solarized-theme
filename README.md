# Trilium Solarized Theme
A [solarized](https://ethanschoonover.com/solarized/) theme for the notetaking app [Trilium](https://github.com/zadam/trilium).

![image](https://user-images.githubusercontent.com/49348667/111087638-050cb300-8523-11eb-819a-ca768fd0948a.png)


## Installation
- Copy the contents of the `solarized.css` file into a Trilium note.
- Change the type of the note to CSS.
- Add the label `#appTheme=solarized-light` (or `dark`)
- Go to options and select this theme 🥳

## Known issues

* Solarized Dark does not play well with CodeMirror.

## Updating the repo

Install sass:

```bash
sudo npm install -g sass
```

After changes, rebuild `solarized.css`:

```bash
sass solarized.scss solarized.css
```
