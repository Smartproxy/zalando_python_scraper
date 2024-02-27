# Zalando Scraper

Scrape Zalando utilising Smartproxy's Web Scraping API

<p align="center">
    <a href="https://dashboard.smartproxy.com/register?page=web-scraping-api%2Fpricing&utm_source=socialorganic&utm_medium=social&utm_campaign=github_website_scraper" ><img src="https://i.imgur.com/v4Z5CXu.png"></a>
</p> 


## Dependencies

```http
BeautifulSoup
```

## Authentication

Once you have an active Web Scraping API subscription, you can try sending a request right from the dashboard Web Scraping API > API playground method tab simply by clicking on Send Request. You will also see an example of curl request generated on the right. 

### This Pyhton code example uses Base64 encoded ```user:pass``` authentication.

| Parser type | Example location         | Download |
| -------------------- | ------------------------ | -------- |
| HTML to JSON        | [zalando_html_parser.py](https://github.com/Smartproxy/zalando_python_scaper/blob/main/zalando_html_parser.py) |``` curl https://raw.githubusercontent.com/Smartproxy/zalando_python_scaper/blob/main/zalando_html_parser.py > zalando_html_parser.py ``` |

## HTML to JSON

This Python script extracts Brand Name, Model, Price, Discount data, Category, Product and Image URLs straight from the HTML of Zalando website and saves them to a JSON file.
