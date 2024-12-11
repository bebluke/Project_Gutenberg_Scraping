# Project_Gutenberg_Scraping

## Describe 
This is a tiny project which is also homework from BDSE WEB SCRAPING CLASS.\
To get all the books in catalogs `Language/zh` from [Project Gutenberg](https://www.gutenberg.org/).
All file save as .txt, content and file name without English characters.

## Project Structure
```
├── book_ids.csv
├── GTBerg_request.ipynb
├── GTBerg_get_id.ipynb
├── README.md
├── requirements.txt
└── project_gutenberg
    ├── 一枕奇.txt
    ├── 三俠五義.txt
    ├── 三國志.txt
    ├── 三國志演義.txt
    ├── 三字經.txt
    └── Excluding multiple .txt files
        .
        .
        .
```


## Installing
`pip install -r requirements.txt`

## Versioning

#### Python Version
- `Python` `3.13.0`
#### Installed Packages
| Package Name | Version  |
|--------------|----------|
| beautifulsoup4 | 4.12.3 |
| requests     | 2.32.3 |
| selenium        | 4.27.1 |

## Results
All 432 books as results in folder `project_gutenberg`.\
[record of scraping](https://youtu.be/Dd2Gt-CsUn4)
