## Instagram Monitor / Scraper

### Installation

Instagram Monitor / Scraper requires the following...

- [Node.js (LTS Version)](http://nodejs.org/)
- [YarnPKG](https://yarnpkg.com/lang/en/docs/install/#windows-stable)

Quick start:

```bash

# Install dependencies
yarn install

# Run application
yarn run start

# Add stuff in your config.json
please leave mongoURI as the same, and configurate your own settings

```

You will need to rename .env.example file into .env

```
IG_USER=yourusernametoaccount
IG_PASS=yourpasswordtoaccount
```

Features:

```bash

# Ability to monitor any instagram accounts ✅
# Able scrape posts & stories ✅
# OCR reader ✅

```

## Todo:

- [x] Ability to monitor any instagram accounts
- [x] Able scrape stories & posts (stories not implemented, but soon...)
- [x] Customizable Discord Embeds
- [x] OCR reader
- [ ] Keyword filter
- [ ] Database Configuration
- [ ] Better way to rotate proxies

## Tips

- Running with an actual Instagram Account, will greatly reduced the chance of rate limiting...
- I ran 5000+ without proxies, and it's running smooth. But I still recommend running proxies.
- If you are planning monitor more accounts, increase your delay.

## Bugs?

Feel free to make an issue about any particular errors or bugs such as internal functionality bugs.

## DISCLAIMER

Please do not abuse this script, any abused from this script will result in banned by Instagram. This is meant for only to be used for educational purpose.

## App Info

### Author

Eric Zhang

### Version

1.0.0

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
