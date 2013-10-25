Panfolio
--------

BEWARE: as of now Panfolio is VERY BUGGY as it's under heavy changes to get rid of JavaScript stuff and it will probably not work correctly. You have been warned.

Panfolio is a tiny Python script to generate a nice simple gallery of all your (say, vacations) pictures. The only reason I wrote this was to get a free coffee on @artmello, who happens to be quite lazy to organize his photos :-)

Demo
----

Wanna see how Panfolio looks like? Check it out: http://caio.ueberalles.net/panfolio-demo

Usage
=====

```
demo@localhost$ ./panfolio
usage: panfolio [-h] [-d DIR] [-n NAME] [-u URL] [-b BLURRY] [-f] [-s]

optional arguments:
  -h, --help            show this help message and exit
  -d DIR, --dir DIR     your photos directory
  -n NAME, --name NAME  the name of your gallery
  -u URL, --url URL     url to be appended to your gallery
  -b N, --blurry N      mark images whose blurry factor is above N
  -f, --fullscreen      makes a full screen pictures-only gallery
  -s, --sharing         enables social sharing features
```

Pros
====

- as fast and as simple as it could get
- renders fine in tablets and smarthphones
- your pictures matter, no cluttering
- addthis.com's support for sharing photos
- automagically rotates thumbnails
- a minimalist lightbox
- elegant!

Cons
====

- you tell me!

Pending
-------

- merge css, js and html into a single file?
- thumbnails caching, maybe?
- support sub-directories?
- infinite scroll? or not?
