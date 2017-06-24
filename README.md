# letiR_website

## How this website has been built

- Website built with [Rmarkdown](http://rmarkdown.rstudio.com/rmarkdown_websites.html");
- [Academicons](http://jpswalsh.github.io/academicons/) for academic icons
- flags come from the [flag-icon](http://flag-icon-css.lip.is) library;
- silhouette images are found on the [PhyloPic](http://phylopic.org) website;
- some R tricks (see the `Rmd` files).


## Dependencies

In order to build this website, the following are needed:
- R(>=3.3.0);
- Rmarkdown(>=1.5);
- We use a customized Makefile do build this website, so you need to use [GNU Makefile](https://www.gnu.org/software/make/) already install on most of (all?) UNIX systems. Windows users should consider using http://www.cygwin.com;
- We used a couple of different packages throughout our different blog posts. The simplest way to get them all is to use [this gist](https://gist.github.com/KevCaz/aaa83151e9d12cc07fbe379e2c32a385].


# Contributing

- Any additional header contain does `header.html`
- To tune the current visual style, modify the `css/perso.css` file.
- Add *jQueries* in `footer.html`
- create a new blog post:

```
  make newpost
```


# To do

- [ ] add a more exhaustive description of contributors/contributions :raising_hand:
- [ ] fix the current wordcloud (it often fails loading) :pray:
- [ ] add tags to posts. (Hugo does it well and it is a valuable feature to add).
- [ ] add contributing for how to make posts
- [ ] add anchor for all h1 / h2 titles (a simple jQuery code should do the job)
