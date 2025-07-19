# Personal site

## About

A [Hugo](https://gohugo.io) page that aims to be simple and flexible. The main page is organized in three parts: presentation, projects, and about. The project list is easily customizable, see [config.toml](config.toml) and [content/home/projects].

## Local build, software, libraries

Run `hugo` in this directory to to build the page manually. The website files are generated in `public/` and can be copied at the root of the website. 

You need to set the proper base URL in [config.toml](config.toml)

The styling and responsive layout are based on [Bootstrap](https://getbootstrap.com). The font used is Google Fonts' [Chivo](https://fonts.google.com/specimen/Chivo).

N.B.: the social-media card is not automatically generated. Rather, the idea is to generate the twitter-card page and then take a screenshot. To display this page, build or preview the website including drafts (run `hugo -D` or `hugo server -D`).

## Licenses

The code is made available under a [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/) licence, i.e., others may freely build upon, enhance and reuse the works for any purposes without restriction under copyright or database law. 

Text and pictures are available under a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) licence, i.e., the works can be freely shared and remixed as long as appropriate credit is given and changes made are indicated.