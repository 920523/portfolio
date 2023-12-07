Load
=======================

This is a report on the loading times of three websites.

Selection
-----------------------

The three websites I chose for this report are [Tre](https://tre.se/), [Telenor](https://telenor.se/) and [Telia](https://telia.se/). They are all combined cellphone operator/internet service provider companies catering to the Swedish market, making them suitable for comparison.

Method
-----------------------

To test the loading times of the different websites I have used <a href="https://pagespeed.web.dev/">PageSpeed Insights</a> to measure mobile and desktop performance (scoring on a scale of 1-100) and the built in developer tools of Chrome for loading times and resources. In order to make the comparison as fair as possible, each page was loaded and then scrolled to the bottom to account for any elements being loaded as the page is unveiled. All websites have three categories of pages in common: a home page, a phones page and a help page. These three pages were tested for each website.


Results
-----------------------

### Tre
<img src="%assets_url%/img/tre.png" alt="Tre" class="screenshot-full">
When it comes to mobile performance, Tre wins both the home and the phones page categories. With a score of 46 and 44 respectively, however, this is not very impressive and the desktop performance was slightly higher (53). The load time, on the other hand, is quite impressive at 1.27 seconds.

Suggestion: reduce unused javascript.

---

### Telenor
<img src="%assets_url%/img/telenor.png" alt="telenor" class="screenshot-full">
Telenor displays a poor mobile performance, the lowest score being in the phones category at 15. The home page on desktop, however, wins the category at a score of 69. The loading times are acceptable at an average of 2.3 (with the highest at 2.62) seconds. 

Suggestion: serving images in next-gen formats (such as webp) would render faster downloads. Shrinking the amount of unused code would also shorten the loading time.

---

### Telia
<img src="%assets_url%/img/telia.png" alt="telia" class="screenshot-full">
Telia is a winner in performance score in the phones category (49 on desktop) and in the help category (45 on mobile and 86 on desktop).

When it comes to loading times, Telia consistenly performs poorly. The shortest time is measured on the help page at 2.54 seconds, which means second place in that category. In the home and phones categories, however, the loading times are by far the very slowest at 4.18 and 4.53 seconds respectively. That is enough of a threshold for users to abort their visit to the website.

Suggestion: according to PageSpeed Insights, reducing unused javascript could cut the loading time by 3 seconds.

---

<iframe class="spreadsheet" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRAc-JZkhFqpkycz982hYw7KLkkN62XylxOO-y_q2w0yzjIlBlei3NXNSar6gsE5SWHzYrTS64K_Z2m/pubhtml?widget=true&amp;headers=false" width="100%" height="275px"></iframe>

---

Conclusion
-----------------------

The loading times somewhat vary between the websites. Personally, I would consider 3 seconds an acceptable loading time on desktop but to avoid user bounce-off I would strive for shorter times than that when building websites. Across all websites it seems a lot of thought has gone into the compression and sizing of images, almost all of them keeping below the 150 kB mark (except for the largest image at 219 kB).

The majority of the pages clear my accepted loading speed mark. The odd one out is Telia with two out of three pages clocking in at above 4 seconds. While these loading times aren't optimal, it is fair to say a lot of work has been done to shorten them. A potential for improvement shared by all sites is reducing unused code that takes up resources that could be used more efficiently. The distinct winner in regard to loading times is Tre, at an average of 1.68 seconds.

---

References
-----------------------

<a href="https://pagespeed.web.dev/">Google PageSpeed Insights</a>

---

_August Levinson_