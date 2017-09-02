

# To Start local server 

jekyll build --watch & firebase serve

# To deploy

firebase deploy


# Stuff you always forget:

## Including image 
{% image round-logo.svg %}


## Image background
background: image-url('image.ext');

# YAML exemple 

layout: ingredient
title: salt 
type: "ingredient"
category: ingredient
color: "#B2E2F3"
image: ingredients/salt.png
summary: "IT IS ALMOST IMPOSSIBLE TO COOK
SOMETHING WITHOUT SALT - SALT IS THE
FAIRY DUST OF THE COOKING WORLD. A
SPRINKLE OF SALT CAN REMEDY MANY
BLAND COOKING FAILURES."
date: 2015-05-29 10:53:47 
related: salt
storage: "Dry & dark in a sealed/airtight container. Salt can absorb moisture from the air, which may cause clumps."
lifespan: "Forever! Kept properly, your salt will outlive the human race."
tags:
- salt
- condiments
- basics