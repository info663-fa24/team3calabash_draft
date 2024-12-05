---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://cdil.lib.uidaho.edu/images/palouse_sm.jpg" %} 

{% include feature/nav-menu.html sections="About CollectionBuilder CSV;About the About Page" %}

## Team 3 Calabash Journal Articles

Multilingual and focused on centering unheard voices, Calabash: A Journal of Caribbean Arts and Letters was a pioneering journal showcasing poetry, literature, and visual arts from across the Caribbean (web archived version). The journal, which Dr. Bishop edited from 2000-2008, had since ceased publishing, and the NYU server that had been hosting the site has been retired. Since there were no existing metadata records, we modified a web scraping script from a recent NYU Libraries Library Carpentry workshop in order to extract article metadata from the Calabash website. The metadata was further prepared using OpenRefine, open source software for data transformation and cleanup. Meanwhile, we also pulled the PDFs from the Calabash site and stored the files in a Github repository.
This site is built using [CollectionBuilder-CSV](https://github.com/CollectionBuilder/collectionbuilder-csv).

CollectionBuilder-CSV is a "Stand Alone" template for creating digital collection and exhibit websites using Jekyll, given:

- a CSV of collection metadata
- a folder of images, PDFs, audio, or video files

[CollectionBuilder](https://github.com/CollectionBuilder/) is an set of open source tools for creating digital collection and exhibit websites that are driven by metadata and powered by modern static web technology.
See [CB Docs](https://collectionbuilder.github.io/cb-docs/) for detailed information.

{% include feature/image.html objectid="demo_001" width="75" %} 

