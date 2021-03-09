# cdc-vaccination-demographic-characteristics

Saving the data that is powering this page to see how it changes over time and how often
https://covid.cdc.gov/covid-data-tracker/#vaccination-demographic

The endpoint was found using browser tools. This is a simple scraper that hits the endpoint and writes it to a json file. If there is a change, then there will be a git diff.

This is a simple demo to try out the technique based on Simon's wonderful git scraping lightning talk.
https://www.youtube.com/watch?v=2CjA-03yK8I


[![Scrape latest data](https://github.com/codecreative/cdc-vaccination-demographic-characteristics/actions/workflows/scrape.yml/badge.svg)](https://github.com/codecreative/cdc-vaccination-demographic-characteristics/actions/workflows/scrape.yml)
