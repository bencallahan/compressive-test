Testing Compressive Images (compressive-test)
================

A series of pages to test compressive images. Based on the conversation started by Jason Grigsby (@grigs) here: http://lists.w3.org/Archives/Public/public-respimg/2013Sep/0015.html

These are a series of test and control pages, each with progressively more images.

## Original Images
I was looking for a wide variety of images and stumbled on the National Geographic wallpapers (http://photography.nationalgeographic.com/photography/wallpapers/). These images are 1600 X 1200 and total around 11M.

## Control Images
The control pages have images which are 500 X 375 saved with a compression level of 12 from the Photoshop Image Processor script. They come in with a total weight of 6.4M.

## Test Images
The test pages have images which are 1600 X 1200 saved with a compression level of 0 from the Photoshop Image Processor script. They come in with a total weight of 4.4M.

## File Names
The HTML files are named to indicate the number of images on each page as well as whether they are a test or control page.

### 5 Images
- 005-test.html
- 005-control.html

### 10 Images
- 010-test.html
- 010-control.html

### 15 Images
- 015-test.html
- 015-control.html

...and so on.

More could certainly be added, but until we’ve done some initial testing we won’t know the best way to structure/instrument these.