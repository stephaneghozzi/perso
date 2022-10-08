# Stéphane Ghozzi's personal page: source code

The source-code files for [https://stephaneghozzi.com](https://stephaneghozzi.com) (which is an alias for stephaneghozzi.github.io).

The files of the are generated via [Hugo](https://gohugo.io) and can be found at [https://github.com/stephaneghozzi/stephaneghozzi.github.io](https://github.com/stephaneghozzi/stephaneghozzi.github.io). After installation, run in this directory:
```
> hugo
```
The files produced in public/ can be copied at the root of the website. Note that you need to set the proper base URL in [config.toml](config.toml)

Styling and responsive layout based on [Bootstrap](https://getbootstrap.com). The font used is Google Fonts' [Chivo](https://fonts.google.com/specimen/Chivo).

Twitter card: it is not automatically generated. Rather, one has to generate the corresponding page (which has the proper styling) and then take screenshot. To generate website with drafts by running:
```
hugo -D
```
Be careful however not to copy the page to the actual website. Another, safer option as no files are generated:
```
hugo server -D
``` 
and go to http://localhost:1313/twitter-card.

## Licenses

The code is made available under a [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/) licence, i.e. others may freely build upon, enhance and reuse the works for any purposes without restriction under copyright or database law. 

Text and pictures are available under a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) licence, i.e. the works can be freely shared and remixed as long as appropriate credit is given and changes made are indicated.