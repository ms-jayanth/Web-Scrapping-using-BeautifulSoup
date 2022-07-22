# Web-Scrapping using BeautifulSoup

## Web Scrapping:
### Introduction
In the time when the internet is rich with so much data, and apparently, data has become the new oil, web scraping has become even more important and practical to use in various applications. Web scraping deals with extracting or scraping the information from the website. Web scraping is also sometimes referred to as web harvesting or web data extraction. Copying text from a website and pasting it to your local system is also web scraping. However, it is a manual task. Generally, web scraping deals with extracting data automatically with the help of web crawlers. Web crawlers are scripts that connect to the world wide web using the HTTP protocol and allows you to fetch data in an automated manner.

Whether you are a data scientist, engineer, or anybody who analyzes vast amounts of datasets, the ability to scrape data from the web is a useful skill to have. Let's say you find data from the web, and there is no direct way to download it, web scraping using Python is a skill you can use to extract the data into a useful form that can then be imported and used in various ways.

### Some of the practical applications of web scraping could be:
- Gathering resume of candidates with a specific skill,
- Extracting tweets from twitter with specific hashtags,
- Lead generation in marketing,
- Scraping product details and reviews from e-commerce websites.

Apart from the above use-cases, web scraping is widely used in natural language processing for extracting text from the websites for training a deep learning model.

### Potential Challenges of Web Scraping
- One of the challenges you would come across while scraping information from websites is the various structures of websites. Meaning, the templates of websites will differ and will be unique; hence, generalizing across websites could be a challenge.

- Another challenge could be longevity. Since the web developers keep updating their websites, you cannot certainly rely on one scraper for too long. Even though the modifications might be minor, but they still might create a hindrance for you while fetching the data.

Hence, to address the above challenges, there could be various possible solutions. One would be to follow continuous integration & development (CI/CD) and constant maintenance as the website modifications would be dynamic.

Another more realistic approach is to use Application Programming Interfaces (APIs) offered by various websites & platforms. For example, Facebook and twitter provide you API's specially designed for developers who want to experiment with their data or would like extract information to let's say related to all friends & mutual friends and draw a connection graph of it. The format of the data when using APIs is different from usual web scraping i.e., JSON or XML, while in standard web scraping, you mainly deal with data in HTML format.


## What is Beautiful Soup?
Beautiful Soup is a pure Python library for extracting structured data from a website. It allows you to parse data from HTML and XML files. It acts as a helper module and interacts with HTML in a similar and better way as to how you would interact with a web page using other available developer tools.

- It usually saves programmers hours or days of work since it works with your favorite parsers like lxml and html5lib to provide organic Python ways of navigating, searching, and modifying the parse tree.

- Another powerful and useful feature of beautiful soup is its intelligence to convert the documents being fetched to Unicode and outgoing documents to UTF-8. As a developer, you do not have to take care of that unless the document intrinsic doesn't specify an encoding or Beautiful Soup is unable to detect one.

- It is also considered to be faster when compared to other general parsing or scraping techniques. 
