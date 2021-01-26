# tadpoles-media-downloader
Hack method to download all of your media from tadpoles.com

***INSTRUCTIONS BELOW***

Quick script I wrote to download all pictures and videos out of tadpoles. To use, do the following:

1.) Copy the following string of text:

javascript:var js = document.createElement('script');js.src = 'https://cdn.jsdelivr.net/gh/vanderjs/tadpoles-media-downloader/index.js';document.querySelectorAll('head')[0].appendChild(js)

2.) Open google chrome (might work with other browsers, but not really tested)

3.) Log into familyinfocenter.brighthorizons.com

4.) Click on the my bright day button in the middle towards the left side of the page

5.) Open an image up, right click on the image, and select "inspect" from the bottom of the list

6.) Scroll up to the top of the Developer Element Screen to find a "mybrighday.brighthorizons.com\..." link. Copy the link and open that link in the current tab.

7.) In the address bar, type the word "javascript" followed by a colon (:) like this:

javascript:

8.) Paste the text you copied earlier so your address bar now looks like this:

javascript:var js = document.createElement('script');js.src = 'https://cdn.jsdelivr.net/gh/vanderjs/tadpoles-media-downloader/index.js';document.querySelectorAll('head')[0].appendChild(js)

9.) Hit ENTER

10.) When the website asks for permission to download multiple files, click "YES". These are your pictures and videos its trying to download.

This sounds *WAY* more complicated than it really is.
Just watch the [video](https://www.youtube.com/watch?v=c54Zx0Dx_A4)
, and if you get lost please feel free to contact me.
