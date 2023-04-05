# How can I collect product information from grocery markets websites?

- [How can i collect product information from grocery markets websites?](#how-can-i-collect-product-information-from-grocery-markets-websites)
- [Intro](#intro)
- [Possible sources](#possible-sources)
- [Available methods](#available-methods)
  - [Public api](#why-use-oauth)
  - [Web scraping](#web-scraping)
    - [How to avoid bot detection](#how-to-avoid-bot-detection)
- [Conclusion](#conclusion)
- [References](#references)


## Intro

This research document will focus on the possible methods of collecting product information, from supermarkets websites.

For the application to work, we need a consistent way to collect product information.
The difficulty is, the application works on a large pool of data, and this data needs to be updated reguraly to keep up with current prices.

Below I will write out the possible methods to solve this problem.


## Possible sources

To collect product data from Dutch supermarkets, there are several sources you can use.
The supermarket's own website is a good starting point, as they often provide a list of products and prices.
Another option is to use price comparison websites, such as Vergelijk.nl or Kieskeurig.nl, which collect and compare prices from multiple supermarkets.
Web scraping tools like BeautifulSoup or Scrapy can also be used to extract data directly from the supermarket's website. Additionally,
web scraping services or data providers like PromptCloud or Import.io specialize in collecting and providing product data from multiple sources

For this project I want to focus on, Albert Hein, Jumbo & Lidl. These supermarkets don't have a public API available for this data,
or if they have it's behind a pay wall. What is outside the budget for this project.
That also means that websites like ShoppingScraper are off limits, because of the high prices for access to their API's.


## Web scraping

Web scraping is a way to automatically extract data from websites.
You use special software to download the code that makes up a website and then pick out the information you want.
There are a few ways to do web scraping, like writing computer code or using browser extensions.
To scrape data, you have to find the parts of the website that have the information you need and figure out how to pull it out.
People use web scraping for lots of reasons, like keeping track of prices or getting data for a school project.
But sometimes web scraping is against the rules or even against the law, so you have to be careful about when and how you do it.

Pros:

Access to vast amounts of data: With web scraping, you can collect a large amount of data in a short period of time from various sources.

Customizable data: Web scraping allows you to collect data specific to your needs, rather than relying on the pre-packaged data that some APIs provide.

Cost-effective: Web scraping is a more cost-effective solution than purchasing data from third-party providers or using APIs that charge for access.

Cons:

Legal and ethical concerns: Web scraping can be illegal if it violates the website's terms of service or if it is used for malicious purposes, such as stealing data or infringing on copyright.

Technical challenges: Web scraping requires technical knowledge and skills, including programming, data manipulation, and understanding of HTML/CSS and other web technologies.

Risk of detection: Websites can detect web scraping activity and block access, which can result in wasted time and resources. Additionally, websites can take legal action against web scrapers for violating their terms of service or infringing on their intellectual property rights.


### How to avoid bot detection

If you're using web scraping to get data from a website, it's important not to look like a bot. If the website thinks you're a bot,
it might block you from accessing the data you need. To avoid getting detected, you should wait a different amount of time between each request you make.
It's also a good idea to make it look like you're using different devices or web browsers, so it seems like a real person is accessing the website.
You should also try not to ask for too much data at once, and instead ask for small amounts at a time.
And don't forget to follow the website's rules and any limits they have on how much data you can get.
By doing these things, you can make sure that you can get the data you need without getting blocked or banned from the website.

