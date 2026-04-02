# Specimen
An elegant brutalist drop-in CSS

## Use
As a drop-in CSS, simply link the stylesheet by adding the following to your `<head>` :
```html
<link rel="stylesheet" href="https://eloi-menaud.github.io/specimen/style.css">
```
## [Page preview](https://eloi-menaud.github.io/specimen/)

## picture preview
![](./preview.png)


## 2 colors based customisation
Since the theme is based on only two colors, you can easily customize it by redefining `--back` and `--front` :
```html
<style>
html:root{
    --back : #fff;
    --front: #000;
}
</style>
```
Example :
![](./colors.png)