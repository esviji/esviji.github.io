---
title: esviji v2 is live!
tags:
  - release
  - Web
  - Firefox OS
---

After waaaay to many month of hard work on the code, almost 3 years after the first release ever, **esviji v2 is [finaly stable](https://twitter.com/esviji/status/686187986371899392)** and released live on [play.esviji.com](http://play.esviji.com/)!

esviji v2 is also already available [in the Firefox Marketplace](https://marketplace.firefox.com/app/esviji/) for all Firefox OS users, including automatic update for those who already installed previous version.

One of the aims of esviji has always been to show that **Web technologies are the best to build applications for all platforms with one single code base**. This second major release is a big improvement, with a much better support of the **very wide range of screen sizes and ratios across the targeted platforms**[^fragmentation], from the smallest smartphones you handle mostly in portrait orientation to the huge connected TVs that now offer 4K resolutions in landscape orientation. I called it [the "WOW effect"](http://play.esviji.com/wow/), and [it seems to be working as intended](https://twitter.com/borisschapira/status/690109733102051328)… ;-)

[^fragmentation]: Even larger than the Android-only already big [fragmentation](http://opensignal.com/reports/2015/08/android-fragmentation/), which is [a bit of a myth](http://rustyshelf.org/2014/07/08/the-android-screen-fragmentation-myth/).

Most of the work all these months has indeed been done on a new interface even more adaptable to any screen size and ratio thanks to [Responsive Web Design](http://alistapart.com/article/responsive-web-design). The interface —previously only a single scalable SVG object— is now a flexible and responsive mix of HTML and CSS for most parts, and the SVG is now only used for the actual game board, where the balls evolve.

For technical inclined people, the responsive part is built with **a lot** of Media Queries and almost only viewport units for elements dimensions and positions.

v1 is still available on [v1.esviji.com](http://v1.esviji.com/) for those of you that are nostalgic or using older browsers without support for new shiny standards.
