# Tranco 100k Crawl

Due to GitHub's storage limits, we cannot include the full raw results of our snapshot crawl of the Tranco 100k here.
Instead, we will make the entire dataset available on our website.
As this will deanonymize us, we have included the crawl result for `example.com` here as an example.

## Crawl Details

Vantage Point: European University

Crawl Date: 2021-02-13 – 2021-02-19

User-Agent: `Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.150 Safari/537.36`

## JavaScript Instrumentation

`browser-inject.js` contains the JavaScript code that is injected into each crawled website ten seconds after `DOMContentLoaded`. It looks available JS objects and attempts to interact with TCF implementations.
