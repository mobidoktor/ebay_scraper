# ebay_scraper
An eBay scraper using Selinium, Beautiful Soup, Firebase and lxml. Intended for use by E-Bay traders to gather data on transactions, automatically bid on desired items, or automate the sales process. May need a little retasking for some of those things.

## Why use ebay_scraper, and not some other eBay scraping library?

ebay_scraper uses Selinium, Beautiful soup, Firebase and lxml,
and is hand-coded in Python with minimal external libaries and 
copy-pasting. This makes it super quick and super light-weight.
You won't be able to find a better ebay scraping library than this one.
Plus, it's fully documented and very easy to use.

**Current version**:
**0.1**: just searches for items at the moment and doesn't use anything except Selinium, 
but I'll add more functionality soon.

You'll need [Beautiful Soup 4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/),
[Python 3.0](https://www.python.org/downloads/) and [Selenium](https://pypi.python.org/pypi/selenium)
installed on your system to use this program.
Click the links for installation details.
You'll also want lxml parser, [Firefox](https://www.google.co.uk/search?q=install+Firefox&oq=install+Firefox&aqs=chrome..69i57j69i60l3j69i61j69i59.2052j0j4&client=ubuntu&sourceid=chrome&ie=UTF-8) and [Geckodriver](https://askubuntu.com/questions/870530/how-to-install-geckodriver-in-ubuntu). Installation details for lxml parser are included lower down the Beautiful Soup installation page. For the rest see their respective links.

Run with `python3 main.py`.

Note: if you run into problems with the Selinium installation, try using `pip3 install -U selinium`.
Any other install problems just raise an issue.
