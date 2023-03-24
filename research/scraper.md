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

There are several sources you can use to collect product data from Dutch supermarkets.
One option is to use the supermarket's own website,where they often have a list of products and their prices.
Another option is to use price comparison websites, such as Vergelijk.nl or Kieskeurig.nl, which collect and compare prices from multiple supermarkets.

## Available methods
### Public API

Public APIs are tools that allow developers to use data or services from other applications or platforms.
For example, you can use an API to show Instagram posts on your website or get weather information from a weather service.
To use a public API, you typically need to sign up and get a special key or token that confirms you're authorized to use it.
Once you're authorized, you can start making requests and getting data from the API. Public APIs usually come with instructions on how to use them,
including what kind of data you can get and how to format your requests.

Pros:

- APIs are often faster and more efficient at retrieving data than web scraping.
- APIs are generally more reliable than web scraping, as the data is provided by the source in a consistent format and can be updated in real-time.
- Using an API is often more secure than web scraping, as scraping may violate a website's terms of service or even be considered illegal.

Cons:

- Some APIs may have restrictions on usage or require payment, whereas web scraping is generally free.
- Using an API may limit the amount or type of data that can be accessed, whereas web scraping allows for more flexibility and customization.

### Web scraping

Web scraping is a way to automatically extract data from websites.
You use special software to download the code that makes up a website and then pick out the information you want.
There are a few ways to do web scraping, like writing computer code or using browser extensions.
To scrape data, you have to find the parts of the website that have the information you need and figure out how to pull it out.
People use web scraping for lots of reasons, like keeping track of prices or getting data for a school project.
But sometimes web scraping is against the rules or even against the law, so you have to be careful about when and how you do it.

Pros:

- Web scraping allows for more flexibility and customization than using an API, as you can extract any data that's visible on a website, not just the data that's provided by the API.
- Web scraping is often free, whereas some APIs may have restrictions on usage or require payment.
- Web scraping can be used on websites that don't offer an API, giving you access to data that may not be available through any other means.

Cons:

- Web scraping is generally less reliable than using an API, as the data may be inconsistent or change frequently.
- Web scraping may violate a website's terms of service or even be considered illegal, depending on the circumstances.
- Web scraping can be slower and less efficient than using an API, especially if the website you're scraping has a lot of data or is slow to load.

#### How to avoid bot detection

If you're using web scraping to get data from a website, it's important not to look like a bot. If the website thinks you're a bot,
it might block you from accessing the data you need. To avoid getting detected, you should wait a different amount of time between each request you make.
It's also a good idea to make it look like you're using different devices or web browsers, so it seems like a real person is accessing the website.
You should also try not to ask for too much data at once, and instead ask for small amounts at a time.
And don't forget to follow the website's rules and any limits they have on how much data you can get.
By doing these things, you can make sure that you can get the data you need without getting blocked or banned from the website.

