# [scottmwyant.com](https://www.scottmwyant.com/)

Take a look aroud, this repository has all the source files for my website.  These files get sent from the GitHub servers to your browser as you move through my site.

## Directory structure

~~~ bash
root
├───pages
│   └───img
│       └───index
├───posts
│   └───img
│       └───2018-08-13
└───styles
~~~

### root

I prefer to have as few files as possible in the root folder.  I have to keep the readme in the root by convention.  GitHub Pages sends traffic to index.html and I need the CNAME record in here to get my custom domain to work.

### pages

This is where I have the pages that define the basic structure to the site.  I'd keep index.html in here if I could.

### pages/img

Wherever there are content pages, I like to have a cooresponding *img* folder at that same level.  At the time of writing, this folder is only supporitng the landing page, index.html.  Yes, the previous two sentences conflict, but by my logic index.html should really be inside the *pages* folder.  The fact that is has to be at the root level is a technical detail, a requirement of my current host.

### posts

Reserved for blog articles.  The articles will be have a date prefix in the filename.

### posts/img

Stores images used in blog articles.  There will be sub-folders for each article, the folder name will by yyyy-mm-dd format, matching the date prefix on the first html file that consumes the content.

### styles

Keeping all css stylesheets in here.  Bootstrap is the first one that gets referenced in the html files.  Next is the file that overrides the styles defined by the Bootstrap selectors.  Then site and finally page specific style sheets.

## Ideas for later

- RSS feed
- Refactor CSS
- favicons

## Links

- [Tree for Windows](http://gnuwin32.sourceforge.net/packages/tree.htm)
- [GIMP for Windows](https://www.gimp.org/)
- [GitHub Pages](https://pages.github.com/)
- [The Noun Project](https://thenounproject.com/)
- [Formspree](https://formspree.io/)
