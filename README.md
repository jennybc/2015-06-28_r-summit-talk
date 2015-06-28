# 2015-06-28_r-summit-talk

Talk at [R Summit and Workshop](http://info.cbs.dk/rsummit2015/)

In case it's not clear from the slides, here's the main gist: Based on my experience ...

  * as an instructor, where I use R Markdown and GitHub heavily in graduate courses, and
  * as an R power user, working to become more of a developer
  
I've formed strong opinions about workflows for R Markdown + GitHub and what the big wins are.

  * Make it a habit to render `.Rmd` and `.R` files to Markdown and, maybe, HTML. Places those files where people can see them, e.g. on GitHub! They help people decide whether they need or want to obtain and run your code.
  * Exploit Markdown and other browsability features of GitHub to make your source repo do double duty as a decent project webpage. Refine your policies about never commiting an intermediate or final product.
  * Advanced GitHub searching, coupled with Winston Chang's [mirror of R source](https://github.com/wch/r-source/) and Gábor Csárdi's [mirror of CRAN](https://github.com/cran/), helps you implement "read the source" in an efficient manner.
  * GitHub Issues are a very versatile way to faciliate conversations that can be, by turns, conversational or technical and code-based.
  * Never pick `NA` as your username for anything.

Want to see the slides?

  * PDF is in this repo: [2015-06-28_bryan-r-summit-talk.pdf](2015-06-28_bryan-r-summit-talk.pdf)
  * View same over [on SpeakerDeck](https://speakerdeck.com/jennybc/talk-at-r-summit-and-workshop-about-using-r-markdown-and-github-in-your-workflow)

Links
========================================================

This talk sort of evolved from my [Feb 2015 talk at the Fields Institute](https://github.com/jennybc/2015-02-23_bryan-fields-talk). So you might want to check out that too.

STAT 545: <http://stat545-ubc.github.io>

__Rough__ notes on GitHub usage in STAT 545:

  * <http://stat545-ubc.github.io/bit004_stat545-use-of-github.html>
  * 2015-06: GitHub [recently announced lots of improvements](https://github.com/blog/2020-improved-organization-permissions) to GitHub Organizations, so my course usage will get much more sane in fall 2015!
  
My [Gist about searching GitHub](https://gist.github.com/jennybc/4a1bf4e9e1bb3a0a9b56#file-r-fcsn-in-wild-search-md)

[The unreasonable effectiveness of GitHub browsability](http://stat545-ubc.github.io/bit006_github-browsability-wins.html)

General resources:

  * The R Project: <http://www.r-project.org>
  * RStudio IDE: <http://www.rstudio.com/products/rstudio/>
  * GitHub: <https://github.com>
  * GitHub Pages: <https://pages.github.com>
  * [Pandoc](http://johnmacfarlane.net/pandoc/): If you need to convert files from one markup format into another, pandoc is your swiss-army knife. 
  * R Markdown: <http://rmarkdown.rstudio.com>
  * `knitr`: <http://yihui.name/knitr/>
  * Git: <http://git-scm.com>
  * [SourceTree](http://www.sourcetreeapp.com) Git client, with a GUI. Available for Windows or Mac.

Great things to read:

  * Carson Sievert's talk [Reproducible web documents with R, knitr & Markdown](http://cpsievert.github.io/slides/markdown/)

  * Ram, K 2013. Git can facilitate greater reproducibility and increased transparency in science. Source Code for Biology and Medicine 2013 8:7. Go to the [associated github repo](https://github.com/karthikram/smb_git) to get the PDF (link at bottom of README) and to see a great example of how someone managed the process of writing a manuscript with git(hub).

  * Karl Broman's tutorial, aimed at stats / data science types: [An introduction to Git/Github](http://kbroman.github.io/github_tutorial/).
