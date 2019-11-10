# DocSearch scraper

This repository holds the code of the DocSearch scraper used to power the hosted
version of DocSearch. DocSearch scaper is used as search for the [rholang/rholang.github.io](rholang/rholang.github.io) implementation. 

## Installation

## Pre-requisites
1. Install Python 3.6. Only this version have no error messages displayed.
2. Install pipenv
  1. run command line with admin rights
  2. pip install --user pipenv
  3. print out where the path of python is with: py -m site --user-site
  4. set path variable (change path to your path) : setx PATH "%PATH%;C:\Users\jetbrains\AppData\Roaming\Python\Python36\Scripts"


## Setup project
1. Open this project with vscode -> cd into /DocSearch-Srapper
2. 



## Related projects

DocSearch is made of 3 repositories:

- [algolia/DocSearch][3] contains the `docsearch.js` code source and the
  documentation website.
- [algolia/docsearch-configs][4] contains the JSON files representing all the
  configs for all the documentations DocSearch is powering
- [algolia/docsearch-scraper][5] contains the scraper we use to extract data
  from your documentation. The code is open source and you can run it from a
  Docker image

[1]: https://community.algolia.com/docsearch/
[2]: https://community.algolia.com/docsearch/run-your-own.html
[3]: https://github.com/algolia/docsearch
[4]: https://github.com/algolia/docsearch-configs
[5]: https://github.com/algolia/docsearch-scraper
