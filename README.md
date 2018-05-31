fforward (for Android)
=======================

Hey!

Forward is an open source Android app that will promote:

- Restaurants that donate money and food to charities. One meal sold = one meal donated.
- Shops that donate clothes to the homeless. Sell one hat = donate one hat to the homeless.
- Groups that clean up trash at the weekends.

Users will log on and see interesting projects and products as they scroll.

# Our Ticket System

We use github issues to write tickets. Tickets are called Feature, or Design. If you see one that looks interesting, you are welcome to click it and try to write the code. Right now we are fixing the design. The fonts + colors are uninspiring. THat needs to change.

## [fforward issues](https://github.com/Microflow/fforward-android/issues)



# fforward Back-End

We have forked RedReader, an open source client for Reddit. Running on the Reddit API allows us to validate fforward for free. We will simplify and change Reddits design until it looks different from the standard Reddit UI. We use Reddit to serve a JSON feed for the prototype. Users do not need to have a Reddit account to use fforward.

For the prototype, we will take a JSON feed from [this subreddit](https://www.reddit.com/r/fforwardTaiwan/). As we expand, we'll add more cities and countries. Each country or city will have its own subreddit. 

Here is an example of a [web-app that uses a re-designed Reddit API](https://codepen.io/Teeke/live/NpZyJB). The user does not know they are using Reddit.

Once we fix the design and get some users, we hope to become a Taiwanese charity!



![Build Status](https://travis-ci.org/QuantumBadger/RedReader.svg?branch=master)
[![Translation status](https://hosted.weblate.org/widgets/redreader/-/svg-badge.svg)](https://hosted.weblate.org/engage/redreader/?utm_source=widget)

RedReader/fforward Features
--------

* Free and Open Source Software - no ads/tracking.
* Lightweight and fast
* Downloads are compressed to save bandwidth.
* Support for multiple accounts.
* Several themes such as Night mode (i.e. dark theme) and Holo
* Swipe posts left and right to perform customisable actions, such as
  upvote/downvote, or save/hide.
* Advanced cache management - automatically stores past versions of
  posts and comments.
* Two-column tablet mode (can be used on your phone, if it's big enough)
* Image and comment precaching (optional: always, never, or Wi-Fi only).
* Built-in image viewer, imgur album viewer, GIF player, and
  webm/mp4/gifv player.


Downloading
-----------

RedReader is available for free on the Google Play store:

https://play.google.com/store/apps/details?id=org.quantumbadger.redreader

[<img src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png"
      alt="Get it on Google Play"
      height="80">](https://play.google.com/store/apps/details?id=org.quantumbadger.redreader)

RedReader can also be found for free on F-Droid:

https://f-droid.org/app/org.quantumbadger.redreader

[<img src="https://f-droid.org/badge/get-it-on.png"
      alt="Get it on F-Droid"
      height="80">](https://f-droid.org/app/org.quantumbadger.redreader)

Translating
-----------

Please help us translate RedReader into new languages, or improve the translations for existing languages!

https://hosted.weblate.org/projects/redreader/strings/

[![Translation status](https://hosted.weblate.org/widgets/redreader/-/svg-badge.svg)](https://hosted.weblate.org/engage/redreader/?utm_source=widget)


Building
--------

RedReader is built using Gradle. Several dependencies are required (and
listed in build.gradle), but these are handled automatically if you use
Gradle.

Detailed instructions on building RedReader using IntelliJ IDEA are in
[BUILD.md](BUILD.md).


License
-------

RedReader is licensed under the GPL, version 3. A copy of the license is
included in [LICENSE.txt](LICENSE.txt).

Bitcoin donations are welcome and accepted at the following address:
`1874wapGxDo2vEp4avisda4gx3SCjsHCQJ`


Thanks
------

Thanks to:

* tomorrowkey.jp, for the [GIF decoder](https://code.google.com/p/android-gifview/) (Apache License 2.0)
* Apache, for various libraries
* The [Jackson JSON processor](http://jackson.codehaus.org/)
* [Joda](http://joda-time.sourceforge.net/)
* [/u/fosterbuster](http://www.reddit.com/user/fosterbuster) for the Danish translation
* [/u/balducien](http://www.reddit.com/user/balducien) and [/u/andiho](http://www.reddit.com/user/andiho) for the German translation
* [remil19](https://github.com/remil19) for the French translation
* [Husam Bilal](https://github.com/husam212) for the Arabic translation
* [Juanma Reyes](https://github.com/jmreyes), [moshpirit](https://github.com/moshpirit), and Andrés Hernández for the Spanish translation
* [Martin Macko](https://github.com/LinkedList) for the Czech translation
* [klenje](https://github.com/klenje) for the Italian translation
* [Beleg-Cuthalion](https://github.com/Beleg-Cuthalion) for the Dutch translation
* [tjernquist](https://github.com/tjernquist) for the Swedish translation
* [Badita Viorel-Octavian](https://github.com/vooctavian) for the Romanian translation
* [András Lengyel-Nagy](https://github.com/lna91) for the Hungarian translation
