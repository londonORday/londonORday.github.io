## London Operations Research Day (LORD)

LORD is a single-track workshop that brings together researchers in operations
and associated fields from the London area, consisting of a limited number of
invited presentations and ample free time for interaction and discussion among
participants. This repository hosts the conference website via GitHub Pages.

### Structure

- The **root** of this repository (`index.html`, `program/`, `registration/`,
  `assets/`) always holds the **upcoming/current edition** of the conference.
- Past editions are archived as self-contained copies in `YYYY-edition/`
  folders (e.g. [2024-edition/](2024-edition), [2025-edition/](2025-edition)),
  each with their own `index.html`, `program/`, `registration/`, and `assets/`.
- To start a new edition: archive the current root site into a new
  `YYYY-edition/` folder, then update the root pages (dates, venue, speakers,
  program, registration) for the new edition.

### Credits

This site is built on
[mikepierce/conference-website-template](https://github.com/mikepierce/conference-website-template),
an HTML/CSS template for small academic conferences, licensed under GPL v3.

## Editing the Template

If you have not edited HTML/CSS to design a webpage before, 
I encourage you to read 
[How to Build a Personal Webpage from Scratch](https://rutar.org/writing/how-to-build-a-personal-webpage-from-scratch/)
by Alex Rutar, particularly the 
[Crash course in HTML and CSS](https://rutar.org/writing/how-to-build-a-personal-webpage-from-scratch/#crash-course-in-html-and-css) 
section.

## Beautiful Math with MathJax (optional)

It may be helpful to include mathematical notation on this website, especially in the abstracts of talks. 
This can be done using [MathJax](https://github.com/mathjax/MathJax).
For an example see the [*programs* page](https://mikepierce.github.io/conference-website-template/program/) of the template site.
To include math in a page of this website, include the lines

````HTML
<script type="text/javascript" async 
    src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=default"> 
</script>
````

in the `<head>` of the HTML file. Then math can by typeset by using LaTeX's math notation enclosed in `\(...\)` delimiters.

## Sitemap (optional)

The file `sitemap.xml` helps search engines understand the structure of your site.
In this file, each instance of "WEBSITE" should be replaced
with the actual address where this website is being hosted.
See the [sitemaps protocol page](https://www.sitemaps.org/protocol.html) for more details.

## Alternatives

The simplicity of the HTML/CSS source for this template is its strongest feature.
For something more slick or modern or sophisticated or complicated:

 - [Hoverboard](https://github.com/gdg-x/hoverboard) is beautiful but requires some tech know-how to setup. 

 - You can build something from scratch based on a 
 [GitHub Pages site with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll) 
 or a template from [Pixelarity](https://pixelarity.com).

