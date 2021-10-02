# Usefull Xpath

## SEO

### Obtain the title

//title

### Headings

//h1

//h2

...

### Obtain the meta description

//meta[@name='description']/@content

## Obtain Viewport

//meta[@name=’viewport’]@content 

### AMP Url

//link[@rel='amphtml']/@href

### Canonical URL

//link[@rel='canonical']/@href

### Meta Robots Tag

//meta[@name='robots']/@content

### Hreflang Meta Tag

//link[@rel='alternate']/@hreflang

### Schema Data

//*[@itemtype]/@itemtype

### Links

//a[@rel="nofollow"] 

//a[starts-with(@href, 'mydomain.com')]

//a[not(starts-with(@href, 'mydomain.com'))]

### GSC Verification

//meta[@name='google-site-verification']/@content

### GTM Verification

//iframe[contains(@src, 'https://www.googletagmanager.com/')]/@src

## Youtube

### Video Title

//h3/a

### Video Url

//h3/a/@href

### Video Views

//*[(@class='watch-view-count')]

### Video Likes and Dislikes

(//*[contains(@class, 'like-button-renderer-like-button')])[1]

(//*[contains(@class, 'like-button-renderer-dislike-button')])[1]

### Video Description

//*[@itemprop='description']/@content

## Others

### DonDominio scrape available domains

//div[contains(@class, 'domainsearch-available')]/div[1]

### Extract email

//a[starts-with(@href, 'mailto')]

### Extract phone

//a[starts-with(@href, 'tel')]

## Interesting Articles

1. [Xpath Cheatsheet](https://devhints.io/xpat)
2. [Xpath Function](https://developer.mozilla.org/es/docs/Web/XPath/Functions)
3. [Xpath in SF](https://www.pmg.com/blog/how-to-use-xpath-in-screaming-frog/)
4. [LaikaTeam Xpath Guide](https://laikateam.com/blog/expresiones-xpath-seo/)
5. [Scrape the SERPS with SF](https://www.screamingfrog.co.uk/how-to-scrape-google-search-features-using-xpath/)
6. [Xpath in Google Sheets](https://dataingovernment.blog.gov.uk/2015/12/22/scraping-page-data-using-importxml-in-google-sheets/)
7. [Xpath Cheatseet Miguel Pau](https://www.miguelpau.es/home/-/blogs/xpath-para-seo-cheat-sheet-y-guia-de-uso)
