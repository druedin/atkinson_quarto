# Atkinson Quarto
A simple custom.scss to use Atkinson Hyperlegible in Quarto presentations. This simply overwrites the fonts of the themes.

More information about the font: https://brailleinstitute.org/freefont

More information about reveal.js themes in Quarto: https://quarto.org/docs/presentations/revealjs/themes.html

## Use

1. Add the custom.css in the same location as your *.qmd document
2. Include the following in your YAML header

```
format:
  revealjs: 
    theme: [night, custom.scss]
```
