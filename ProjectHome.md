# Newspaper Column Layout jQuery Plugin #

[Click here for the demo.](http://kenneth.kufluk.com/google/js-columns/)

This jQuery plugin is designed to help with the creation of newspaper-style column layouts in HTML.

While CSS3 has a variety of column-style properties, these are not yet widely implemented, and none help with the creation of page-based layouts.

One of the finest examples of this sort of newspaper layout is the [New York Times Reader](http://timesreader.nytimes.com/timesreader/index.html) AIR app.  This plugin has similar goals, but does not intend to mimic or replicate that functionality.

It is thought that when reading news-based information, the human eye finds it easier to digest in a column length of between five and eight words, which makes skimming easier, and prevents the possibility of losing track of the line from one side of the page to another.

This project has the following goals:
**display columns filling the container** allow smooth paging, without a reload
**smoothly adjust the page when resizing the window** allow columns spanning images
**allow interstitial content, like quotes (todo)**

## How does it implement columns? ##

![http://kenneth.kufluk.com/google/js-columns/image-how.jpg](http://kenneth.kufluk.com/google/js-columns/image-how.jpg)

Once loaded, the plugin replicates the content into an appropriate number of columns.  It then moves then up and down as required, while masking out the viewport.

Click the last column to move one page out of view, and bring in the next page.

## Demo ##
[Click here for the demo.](http://kenneth.kufluk.com/google/js-columns/)

## Known Issues ##
  * When only one column is shown, just make a long scrolling page (eg, to suit iPhone)
  * Add caption to large image
  * When the image is too large, it can crop
  * Add interstitials:  quotations and images between paragraphs (with captions?)
  * Add calculated percentage gaps between columns
  * Sometimes the paging calculates wrong
  * Add keyed paging and mouse roll
  * Sometimes hover doesn't work (Chrome)
  * Correctly allow for header and footer spacing
  * Remove the need for a stylesheet

Speed of fixing these issues will depend on interest from implementors.
Let me know.