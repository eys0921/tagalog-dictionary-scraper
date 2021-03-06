# Tagalog Dictionary Scraper :ledger:  [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Check%20out%20Tagalog%20Dictionary%20Scraper!%20Ating%20pag-ibayuhin%20ang%20ating%20talahuluganan.%20%40github%20https://github.com/raymelon/tagalog-dictionary-scraper)

>***Ating pag-ibayuhin ang ating talahuluganan!***

Collects [Tagalog](http://tagaloglang.com/) words from [tagalog.pinoydictionary.com](http://tagalog.pinoydictionary.com/), a database of [Tagalog](http://tagaloglang.com/) words powered by Cyberspace.ph Web Hosting using web scraping and web crawling techniques.

**24,868 words (as of Oct 20, 2016)**

![](https://reposs.herokuapp.com/?path=raymelon/tagalog-dictionary-scraper)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)
[![Build Status](https://travis-ci.org/raymelon/tagalog-dictionary-scraper.svg)](https://travis-ci.org/raymelon/tagalog-dictionary-scraper)
[![Code Health](https://landscape.io/github/raymelon/tagalog-dictionary-scraper/master/landscape.svg?style=flat)](https://landscape.io/github/raymelon/tagalog-dictionary-scraper/master)
[![codecov](https://codecov.io/gh/raymelon/tagalog-dictionary-scraper/branch/master/graph/badge.svg)](https://codecov.io/gh/raymelon/tagalog-dictionary-scraper)

[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)]()

## How is it done? :muscle:
Each webpage is loaded and parsed, extracting the words enclosed in `<dt>` tag.

Included is [`tagalog.pinoydictionary.com`](http://tagalog.pinoydictionary.com/) `html` [snippet](https://github.com/raymelon/tagalog-dictionary-scraper/blob/master/tagalog.pinoydictionary.com%20html%20snippet.html) containing the source of
[`http://tagalog.pinoydictionary.com/list/a/`](http://tagalog.pinoydictionary.com/list/a/) to serve as guide and overview on how dictionary words from the page are extracted.

**Disclaimer:**
I do not own the `html` code cited above, it is owned by [tagalog.pinoydictionary.com](http://tagalog.pinoydictionary.com/).

## How did the project started? :thought_balloon:
Originally it is intended for a [Scrabble ®](http://www.scrabble.com/) Tagalog dictionary database, but other uses may vary.

## Tools :pencil2:
- [Python 3+](https://www.python.org/) :snake:
- [Beautiful Soup 4.5.1](https://www.crummy.com/software/BeautifulSoup/) :ramen: :package:
```
  python -m pip install -U pip beautifulsoup4
```

## Notes :pushpin:
- `tagalog_dict.txt` is where the scraper [`collect_tagalog.py`](https://github.com/raymelon/tagalog-dictionary-scraper/blob/master/collect_tagalog.py) puts the collected words.
- The output file [`tagalog_dict.txt`](https://github.com/raymelon/tagalog-dictionary-scraper/blob/master/tagalog_dict.txt) will be updated from time to time to ensure up-to-date collection. :date:

## License [![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)
[GNU General Public License 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
