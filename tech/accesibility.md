Use [Pa11y](https://github.com/pa11y/pa11y) to check how accessible is the website

### How to
* `node -g pa11y`
* `pa11y -s WCAG2AAA -r json https://nhsconnect.github.io/prm-practice-migration-staging` this runs `pa11y` against the staging website using the WCAG2AAA standard and exports the output in json format 