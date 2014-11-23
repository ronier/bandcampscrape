# BandCampScrape
==============

**BandCamp Scrape** makes easy to download albums from BandCamp
  creating a directory adding ID3 information to the songs.

Usage
---------

First, install with:

```bash
pip install bandcampscrape
```

Then, just call it from  the CLI passing the URL of the album that you
want to scrape:

```bash
bandcampscrape <url>
```

It also can be used like :

```bash
bandcampscrape --album_url=https://decontextoydetextura.bandcamp.com/album/ep
```

TODO
--------------
- Pass a url and download all the albums from that band
- Add tests
