# SG Rate scripts
1. DBS FD rates as per Telegram group scraped by R (H/T) overlaid w/ 3mo Compounded SORA scraped by MAS API + dropdown menu filter by date

* improve: auto writing into df instead of a csv, which is now manually written into csv
* need to make scale static for better viz
* python scrape from DBS website> df>cron job

2. 1,3,6mo Cpd SORA overlay w/ US10Y (MAS API)

3. US10Y changes over week to see how curve shifts (Quandl)
