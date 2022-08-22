---
title: "Noodles: A purpose-first Startpage"
image: 
  image: /assets/images/noodles-bootstrap-startpage-lg.png
  thumbnail: /assets/images/noodles-bootstrap-startpage-thumb.png
  caption: "my no-nonsense web startpage"
---

{% include icon-github.html username="EccTM" %}/[Noodles](https://github.com/EccTM/Noodles)

**Noodles** is a Bootstrap 5.1 based startpage that I made for myself after finding my Bookmarks bar had started to overflow with subfolders and shortcuts.

## Origin

I started looking online for an alternative to my poor Bookmarks bar, and came across some beautifully designed startpages, but they had an issue. They all prioritised style over practicality, and often, ended up adding more clicks to achieve the same task.

I decided to take the oportunity to review what sites and shortcuts I actually use, and simplify it everything down to a single page of shortcuts that take me to the places I visit most.

## Features

- simple logo buttons for each shortcut
- shortcut names appear via tooltip on hover
- swappable light and dark themes (that are remembered per-device)

## Unplanned Improvements

Seeing as I threw it together for my own use, the shortcuts are currently hard-coded into the `index.html` file. I'd like to expand on it and read the shortcuts in from a json file.