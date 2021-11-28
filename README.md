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

### Images without Alt

//img[not(@alt)]/@src

### Links

//count(a[@rel="nofollow"])

//count(a[starts-with(@href, 'mydomain.com')])

//count(a[not(starts-with(@href, 'mydomain.com'))])

### GSC Verification

//meta[@name='google-site-verification']/@content

### GTM Verification

//iframe[contains(@src, 'https://www.googletagmanager.com/')]/@src

//script[contains(@src, 'googletagmanager.com/gtm.js?id=')]/@src

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

### Scrape available domains from DonDominio

//div[contains(@class, 'domainsearch-available')]/div[1]

### Extract email

//a[starts-with(@href, 'mailto')]/@href

### Extract phone

//a[starts-with(@href, 'tel')]/@href

### Tag Contains certain text

//tagname[text()='text']

## Interesting Articles

1. [Xpath Cheatsheet](https://devhints.io/xpat)
2. [Xpath Function](https://developer.mozilla.org/es/docs/Web/XPath/Functions)
3. [Xpath in SF](https://www.pmg.com/blog/how-to-use-xpath-in-screaming-frog/)
4. [LaikaTeam Xpath Guide](https://laikateam.com/blog/expresiones-xpath-seo/)
5. [Scrape the SERPS with SF](https://www.screamingfrog.co.uk/how-to-scrape-google-search-features-using-xpath/)
6. [Xpath in Google Sheets](https://dataingovernment.blog.gov.uk/2015/12/22/scraping-page-data-using-importxml-in-google-sheets/)
7. [Xpath Cheatseet Miguel Pau](https://www.miguelpau.es/home/-/blogs/xpath-para-seo-cheat-sheet-y-guia-de-uso)
8. [Xpath for Ecommerce](https://salt.agency/blog/how-to-easily-map-product-redirects-in-ecommerce-migrations/)
