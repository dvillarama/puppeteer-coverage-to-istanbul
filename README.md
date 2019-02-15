# combine

Converts and combines Puppeteer coverage into an istanbul coverage report

# setup
clone repo
cd to repo
yarn install

# usage
```
Usage: combine
    -i <input directory of puppeteer coverage files>
    -o <output directory for converted files>
```

# Example
```
./combine -i sample -o output
```

The coverage report should be in a new directory `html-report`
```
open ./html-report/index.html
```

# Notes:
- Using a forked version of puppeteer-to-istanbul
-  "puppeteer-to-istanbul": "https://github.com/Science37/puppeteer-to-istanbul"
