---
title: Effective Web Design
author: Philippe Grosjean
date: '2017-11-28'
slug: effective-web-design
categories:
  - "User interface"
tags: ["web", "design"]
summary: "Main points to consider when designing Web sites"
---

A couple of idea gathered from various readings about Web design, in brief.

## Key aspects

- **Usability** is more important than **visual design**.
- **Quality** and **credibility** are essential.
- **Simplicity**: KIS principle.
- **Consistency**: yes, con-si-sten-cy!!!
- **80/20 rule (Pareto principle)**: 80% of result comes from 20% of the users. Identify these 20% and optimise the site for them.

## Conventions

- **Stick on conventions**: reduce the learning curve by building on existing user’s knowledge.
- _**Innovate only when you know you have a better idea.**_
- **Baby-Duck-syndrome**: users tend to stick with the first design they learn.

## General layout

- **Visible language**: organise - economise (simplicity + clarity + distinctiveness + emphasis). 
- **Law of proximity**: group elements spatially for a better perception of their relationship.
- **Split large pages**: web pages are not books. Split large content into several pages and make navigation between them obvious, simple and handy.
- **Feature exposure**: 1-2-3-done step, large buttons with visual effects = modern web design, … but modern web designs are also criticised for that!
- **Adjust the layout for different sizes** (think smartphone -> tablet -> PC)

## Graphical elements

- **Fonts**: limit their number. Max three fonts in max three point sizes.
- **Page width**: max 18 words/50-80 characters per lines. Constrain max page width to match it.
- **White space**: reduce cognitive load, help users to scan the page effectively with large white spaces.
- **Images**: pictures are eye-catching, use them wisely to convey the message and/or focus attention.
- **Icons** should be used where they can easily be recognised (e.g., RSS-feed, Home, Search button, …). [Fonts Awesome](http://fontawesome.io) or equivalent are very useful here.

## Effective communication

- **Rapid information**: the first page must be quickly informative about the site content and about recent changes. Here is an [example](http://themes.laborator.co/#theme=kalium) of a site pushing this concept very (too?) far.
- **Inverted pyramid**: place summary and major points or conclusions at the top of an article.
- **Go directly to the point**, e.g., *"**Free** service, sign up here"*. Even better if "Free" stands out. Use short and concise phrases.
- **Effective writing**: do not write web pages like textbooks. Avoid promotional writing, avoid long paragraphs without images, or words in bold (arghh! But I **like** this), italic or with links.
- **Videos**. Use (and abuse) of very short video presentations as complimentary material, but only to convey the message (no funny cats videos, just to amuse -and distract- your readers!). Think also at [animated gifs](https://giphy.com).

## Navigation

- **7±2 principle**. Human’s short-term memory can retain 5-9 things at one time. Limit number of options in navigation menus to 7 (but controverses exist, see breadth vs depth hereunder). In any case, reduce short-term memory load as much as possible.
- **Breadth vs depth**. If you display less at a time, you need to go deeper in the hierarchy to cover the same set of options. There is a tradeoff to find between breadth and depth.
- **Hierarchical structures** reduce complexity (Simon’s law), e.g., in menus.
- **3-click-rule**: many users would stop using the site if they don’t find what they are looking for in 3 clicks max. But if they are able to know exactly where they are, they accept more (the 3-click-rule only applies to exploration in "unknown zones").
- **Enable shortcuts** for frequent users.
- **Welcome trial-and-error approach**: give informative feedback + use simple error handling + ease reversal of actions.

## Usability

- **Scan-click-behaviour**: users don’t read but scan pages and click in the first link that looks more or less to what they are looking for. Keep this in mind 110% of the time when designing/writing a web page.
- **Banner-blindness**: users are used to advertisements and thus, tend to ignore large and colourful banners that look like advertisements.
- **Focus attention**: use eye-catching elements (pictures, bold text, …) wisely to gently direct the reader. Avoid flashing elements or animations that catch too much attention and are distracting, on the contrary.
- **Immediate intuition**. Any product that needs a manual to work is broken, this is certainly the case for web sites: web page should be obvious and self-explanatory.

## Perception

- **Features exposition**: let the user see clearly what functions are available.
- **Give control**: users want to have control all the time.
- **Impatience**: web users are impatient and want instant return.
- **2-second-rule**. Regarding reactivity, avoid anything that would take more than two seconds to load.

## Test your design

- **Test early, test often** TETO-principle
- **Test is an iterative process**: change - test - change - test, etc.
- **Test with naive/new users** (and don’t trust your own feeling: you, as the designer, are not a naive/new user)
- **Test on all browser configurations** that will be used at least 80% of the time (think about the Pareto principle), and make sure to provide readable -but not necessarily optimised- fallback solutions for the rest, e.g., very old browsers, or Javascript disabled.

## Miscellaneous

- **Copyright**: think about license for your site, your data, your images. Don't enfringe others rights. Give due credits, in particular for pictures you use.
- **Printing style** for HTML pages: look how your page look like when printed, if it is pertinent, and design special CSS code for printed material.
- **Inspiration**: scan web sites with a critical eye. Get inspired by good ideas.
- **Images and binary resource** should be kept outside version control repositories as much as possible, but it complexifies the whole system.
- **URL shortener**: good for short-term use, but to be prohibited for web sites, unless you have full control on them, including the URL they point to, in order to adapt them (e.g., [Rebrandly](http://www.rebrandly.com)).
- **Static pages**: you can go very far with static pages generated with [Jekyll](https://jekyllrb.com) or [Hugo](https://gohugo.io), and you get also full reproducible production including data analysis using [Bookdown](https://bookdown.org/yihui/bookdown/) or [Blogdown](https://bookdown.org/yihui/blogdown/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTczMDc4MjE0NF19
-->