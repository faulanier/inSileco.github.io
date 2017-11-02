## inSileco blogdown

[![Build Status](https://travis-ci.org/inSileco/inSileco.github.io.svg?branch=dev)](https://travis-ci.org/inSileco/inSileco.github.io)

The overarching goal of this blog is quite straightforward: tackle challenges and opportunities provided by this new era of open-access and computationally intensive research in the field of ecology.



### Getting started

#### Install blowgdown

```r
if(!require(devtools)) install.packages('devtools')
devtools::install_github('rstudio/blogdown')
```

If you want more info on how this package works, have a look at the blogdown [documentation](https://bookdown.org/yihui/blogdown/), you can also have
a quick look at [this blog post](https://blog.rstudio.com/2017/09/11/announcing-blogdown/).

#### Deploy the server

0. Make sure you're at the `HEAD` of the`dev` branch and in the inSileco.github.io folder.
1. Open a terminal and run: `Rscript -e 'blogdown::serve_site()'`
2. Site is available at `http://127.0.0.1:4321` from your browser.

If any changes are made on source files, the site will be autogenerated and changes will be displayed at the `localhost` address (`http://127.0.0.1:4321`).

#### Writing your own post

0. Make sure you're at the `HEAD` of the `dev` branch and in the inSileco.github.io folder.
1. You can esily create a new empty post with:

```r
Rscript -e 'blogdown::new_post('MY_TITLE')'
```

#### Colors

- Main: "#3fb3b2";
- Yellow-logo: "#ffdd55";
- red code: "#c7254e";
- blue twitter: "#1b95e0";
- purple kevcaz: "#8555b4"
- So the palette is `c("#3fb3b2". "#ffdd55", "#c7254e", "#1b95e0", "#8555b4")`


#### Badges

![](https://img.shields.io/badge/inSileco-InDevelopment-3fb3b2.svg)

![](https://img.shields.io/badge/inSileco-UnderReview-ffdd55.svg)




## TODO

- [ ] Describe all YAML headers options;      
- [ ] KevCaz would like to know if we can add a custom yaml field;      
- [ ] Set a repository to include how the wordcloud was generated and link this
repo in the website.    
