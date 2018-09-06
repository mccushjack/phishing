# Phishing Data Science example
## Goal: 
Given a list of suspected phishing url can we build a machine leaning model to predict malicious URL's

## Process

### Step 1
    get list of potential phishing URL's
    go to  https://openphish.com/feed.txt
### Step 2
    Get list of not suspected phishing URl's from Common Crawl
    We cann't train on all url so we'll need to find a way to sampple
    OpenDNS maintains random sample of 10,000 domains on github
    Go to https://github.com/opendns/public-domain-lists get list of domains
    once we have list use python to get complete URL list for all domains
    https://dmorgan.info/posts/common-crawl-python/
    
    