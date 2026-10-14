# TextFold Gallery

Landmark papers from eight fields, plus a Wikipedia article and a GitHub README, to fold and unfold: **https://chenxiachan.github.io/textfold/gallery/**

Each page is the static TextFold reader holding one text at five levels, from the full text to a one-screen map, in English, Chinese and German. It opens at the Topic level; pinch, or press 1 to 5, to go down to every word.

Each text belongs to its authors and keeps its license, named under its title: Creative Commons for the papers and the Wikipedia article; the README is shared with its author's consent. TextFold is not affiliated with the authors; the levels, links and translations were made by AI. An author who would like a paper taken down can [open an issue](https://github.com/chenxiachan/paperfold-gallery/issues).

`fixes/` holds the proofreading: corrections to the AI's levels and translations, checked against each text, which the build puts over the model's text. It will not build a paper without them.

This repository holds the gallery; the website serves it ([TextFold's site workflow](https://github.com/chenxiachan/textfold/blob/main/.github/workflows/site.yml) copies it in). Its own GitHub Pages, at the gallery's first address (chenxiachan.github.io/paperfold-gallery), sends each page on to its new one.

Made by [Xia Chen](https://chenxiachan.github.io/) with [TextFold](https://github.com/chenxiachan/textfold), formerly PaperFold (Apache License 2.0, see [NOTICE](NOTICE)).
