---
#(don't forget to change file name to yyyy-mm-dd-title.md)
# You MUST Modify these:
title: ${the full title of the software}
author: ${author name}
date: ${date}
published: false   # set to true to make it public
tags: # [${primary tag}, ${additional tags -optional-}]
# modify these if you want to:
# image: ${image url} # adds an image to the thumb nail used to link to this post. 
# DON'T MODIFY THESE:
layout: post
---

### Test Title

test content

this allows for limmited multimedia support, and you will need to either know how to use jekyll or link it with absolute URI from an external source to get it to work.
The later is recomended fo rmost people. 

gobldey gook

test image w/ jekyll liquid comments (image is in the `/site-src/images` directory already)

![test-image]({{ "/images/DecidabilityDiagram.png" | absolute_url }})


test image w/ external media:

![Test-Image-2](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSXqq3j05ykEU69GBIwyuuuiFhePdmiIIk3zMJ6gfim7Sv3yaJ0v86GjGf4_W9P-BqgHjA&usqp=CAU)


that is all for now

