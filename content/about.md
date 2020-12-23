---
appendix:
  acknowledgments: |
    We thank the authors of the [Wowchemy](https://wowchemy.com) theme, [tufte.css](https://github.com/edwardtufte/tufte.css), and the
    [Distill](https://distill.pub) framework for inspirations. Many users in the R community have asked
    for a Distill-like Hugo theme directly or indirectly, including but not limited to
    [Emi Tanaka](https://emitanaka.org/r/posts/2018-12-12-scientific-and-technical-blogging-radix-vs-blogdown/),
    [Duncan Garmonsway](https://twitter.com/nacnudus/status/1098910973266743296),
    [Frank Harrell](https://stackoverflow.com/q/54388451/559676),
    [Josiah Parry](https://twitter.com/JosiahParry/status/1231280231543164928), and
    [Alison Hill](https://twitter.com/apreshill/status/1070550028274429952). We are not sure if this Hugo
    Prose theme would make it easier or even harder to answer the frequently asked question "blogdown or
    distill?"

    The images on this page are from Wikipedia entries [Stoicism](https://en.wikipedia.org/wiki/Stoicism)
    and [清明上河图](https://zh.wikipedia.org/wiki/%E6%B8%85%E6%98%8E%E4%B8%8A%E6%B2%B3%E5%9C%96). The
    CSS style for draft posts was borrowed from Fabian Tamp's
    [paperesque](https://github.com/capnfabs/paperesque/) theme. [Wladimir Palant's tutorial](https://palant.info/2020/06/04/the-easier-way-to-use-lunr-search-with-hugo/)
    helped a lot with our implementation of the client-side search.
author: د.احمد اللقماني الحربي
categories:
- plot_ly
- layout
- add_trace
features:
- +toc
- +number_sections
- +sidenotes
- -citation
menu:
  header: 
    name: عننا
    weight: 2
tags:
- menu
- TOC
- sidenote
- appendix
- citation
- numbered section
title: Radarchart (PLOTLY) - الرسم الرداري 
---

**Radarchart** is a minimalist theme derived from the [**XMin**
theme](https://github.com/yihui/hugo-xmin), and inspired by
[Wowchemy](https://wowchemy.com) (previously known as the Academic theme),
[Distill](https://distill.pub), and
[tufte.css](https://github.com/edwardtufte/tufte.css). This theme itself is
completely plain-text and lightweight, and does not use any icons, images, or
emojis.[^1] By default, the theme only uses two JavaScript libraries, MathJax
and highlight.js, and they are loaded only when necessary. The rest of
JavaScript is written from scratch and also relatively short. This theme does
not use any CSS frameworks, and the full CSS code is also written from scratch
(about 300 lines).

[^1]: This example website does contain images and videos as demos, though.
<div class="quote-right">

> It is not the man who has too little that is poor, but the one who hankers after more.
>
> --- _Letters from a Stoic_

</div>



# Home page
## Authors

This page introduces the features of this Hugo theme that you can fiddle with.


# Posts

## Plot_ly(theta,r)



``` html
 

add_trace(r = c(0, 1, 2, 3, 4, 3, 5, 6), theta = c(180, 225, 270, 315, 180, 225, 270, 315))

```
 


<div class="fullwidth">

{{< figure src="https://static.wixstatic.com/media/668f28_0cc79e6c141c4ac8ab09e08df58939bc~mv2.png/v1/fill/w_840,h_539,al_c,lg_1,q_90/newplot.webp" alt="History of stoics" caption="Figure 3.1: Beginning around 301 BC, Zeno taught philosophy at the Stoa Poikile (\"Painted Porch\"), from which his philosophy got its name. Unlike the other schools of philosophy, such as the Epicureans, Zeno chose to teach his philosophy in a public space, which was a colonnade overlooking the central gathering place of Athens, the Agora." >}}

</div>


**Table of contents**

**Number sections**

**Appendix**

Custom fields

**Citation**


 


## Layout()

The layout R function specifies complex plot arrangements.


**Table of contents**


1. layout()

  1.1. layout(polar = list)

  1.1.1 polar (list(radialaxis = list)

  1.2 layout(showlegend ,showline )

  1.3 layout(title)

  1.4 layout(scene = list)

**Number sections**

**Appendix**

Custom fields

**Citation**






## Add_Trace(theta,r) 




**Table of contents**

**Number sections**

**Appendix**

Custom fields

**Citation**


## Add_Trace(theta,r) and plot_ly(theta,r)




**Table of contents**

**Number sections**

**Appendix**

Custom fields

**Citation**





## Data.frame(theta,r)

``` html
data.frame(r = c(0,1,2,3,4,3,5,6), theta = c(180,225,270,315,180,225,270,315))
```
<div class="fullwidth">

{{< figure src="https://static.wixstatic.com/media/668f28_9612b0495bf045a9b92d41bc4718451d~mv2.png/v1/fill/w_1805,h_371,al_c,q_90,usm_0.66_1.00_0.01/Screen%2520Shot%252020%2520_edited.webp" alt="History of stoics" >}}

</div>

 


**Table of contents**

**Number sections**

**Appendix**

Custom fields

**Citation**

 
# Drafts

## Articles

** Author **


