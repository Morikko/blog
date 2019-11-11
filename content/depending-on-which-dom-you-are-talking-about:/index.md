---
title: "Depending on which DOM, you are talking about:"
description: "The one in a web extension page -> yes"
date: "2019-04-05T15:36:55.748Z"
categories: []
published: true
canonical_link: https://medium.com/@Morikko/depending-on-which-dom-you-are-talking-about-a83608d8c6dd
redirect_from:
  - /depending-on-which-dom-you-are-talking-about-a83608d8c6dd
---

Depending on which DOM, you are talking about:

-   The one in a web extension page -> yes
-   The one in the background page -> yes if you fetch it with browser.runtime.getBackgroundPage(), you access to the window object
-   The one in an interface page (popup, panel…) -> yes but it could be hard to put the Jasmine interface as well

If you are thinking about another DOM, I will need more information.
