---
layout: post
title: "Block, Inline-Block, Inline"
date: 2016-02-29
categories: 
keywords:
description: "Display Values"
comments: true
categories:
- welcome
tags:
- welcome
- hello-world

---

Block, inline-block, and inline are all different types of display values. They all have different properties and characteristics that make them more useful in one case or another.

Block elements are elements that can have a set width and height. If no specific width is set, then they will fill up their entire parent container, and if no specific height is set, they will expand to fit their entire child elements. Blocks can also be assigned margins and padding around them so that there’s some space between different elements. Blocks will also automatically move to a new row when they’re created and won’t respond to the vertical-align property. To get around this, the programmer must use floats to get them on the same line. This will maintain block functionality, but will create multiple rows. However, this can cause a few messy problems, which may make either inline-block or inline the better way to go for certain elements.

Inline elements are quite different from block elements. First of all, they don’t have any way to be assigned a height or width size. They also flow in one line, instead of moving to a new line like block elements do. One site said to think about inline elements as boxes that act like text in a paragraph. Inline elements also respond to white-space settings and the vertical-align property, unlike block elements. But, inline elements ignore top and bottom margins, but will apply left and right margins and padding, unlike block elements, which will apply all of those. A programmer can automatically turn an inline element into a block element, however, by floating it right or left.

Inline-block elements are the last type of display value for this post. They’re a bit like a combination of the two previous display values, block and inline. Inline-block elements are a way to make elements inline but have them maintain their block characteristics, like different heights, widths, margins, and padding. This may seem like the perfect solution, but there are still some problems with inline-block elements. One problem is that the elements get lined up with the bottom of the different elements versus the top. This can be easily fixed, however, with the vertical-align property. Another problem can be the whitespace surrounding inline-block elements. The whitespace won’t go away even if the margins are set to 0, so the programmer must actually set them negative.

There are pros and cons to all of these different display values. There’s not one good answer to use for every situation, it just depends on what the programmer is trying to accomplish with their code. If they want something to look a certain way, there will be one of these display values that will more closely match that their goal is, and in that case, they should use that one.

http://designshack.net/articles/css/whats-the-deal-with-display-inline-block/
http://www.impressivewebs.com/inline-block/
http://www.impressivewebs.com/difference-block-inline-css/
