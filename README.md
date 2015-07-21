## A boilerplate integration of [`reveal.js`](https://github.com/hakimel/reveal.js) and [`jekyll`](http://jekyllrb.com/docs/home/)

You should be able to clone this, and in the top of the directory, run `jekyll serve` before navigating to `http://127.0.0.1:4000/slideshow` and seeing the slideshow which is currently served up from the `slideshow` folder.

Important files for tweaking include:
+ `_layouts/slide.html` is the [`jekyll` layout](http://jekyllrb.com/docs/structure/) used for the slide shows.
+ …which in turn relies on `_includes/slide_{footer,head,header}.html` for some basic scripting and styling.

This repository was initialized with `jekyll new` and currently integrates `reveal.js v3.1.0` (which you can find in `lib/`).
