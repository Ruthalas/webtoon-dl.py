Webtoon-dl.py
=============

Comic downloader/scraper for http://www.webtoons.com. Download individual comics or entire galleries. Output as CBZ archives or as sets of folders containing numbered images.

Requires
--------

 * `>=Python3.6`
 * [requests-html](https://github.com/kennethreitz/requests-html)

Installing
----------

`pip3 install requests-html` or whatever

Usage
-----

```
usage: webtoon-dl.py [-h] [-r] [-o OUTPUT] webtoon_url [webtoon_url ...]

  webtoon_url           Url to webtoon comic or creator page.
                        Multiple URLs may be entered.

optional arguments:
  -h, --help            show this help message and exit
  -r, --raw             Save image files to folder instead of CBZ output.
  -o OUTPUT, --output OUTPUT
                        Path to output directory. Defaults to current directory.
```
