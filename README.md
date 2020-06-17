# Social Scrape Bot

> Python app to collect social media data and append daily results to sheets file on Google Drive
---
> Scrape is running on a NodeJS server with a daily cron job
---
> This data is collected from Instagram, Facebook, YouTube to help Marketing department track crucial data.

### Framework Versions & Required Packages
This is app is running on:

- <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/1024px-Python-logo-notext.svg.png" height="20"> Python v3.8

```shell
// Scraping
$ pip install requests bs4

// Path
$ pip install dotenv pathlib

// Google Drive Auth
$ pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
```

- <img src="https://nodejs.org/static/images/logo-hexagon-card.png" height="20"> Node v12
```shell
// Server
$ npm install express

// Cron
$ npm isntall node-cron shelljs nodemailer
```
