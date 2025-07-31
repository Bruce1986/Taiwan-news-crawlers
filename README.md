# Taiwan-news-crawlers

🐞 [Scrapy](https://scrapy.org)-based Crawlers for news of Taiwan including 10 media companies:
1. 蘋果日報
2. 中國時報
3. 中央社
4. 華視
5. 東森新聞雲
6. 自由時報
7. 公視
8. 三立
9. TVBS
10. UDN


## Getting Started

```
$ git clone https://github.com/TaiwanStat/Taiwan-news-crawlers.git
$ cd Taiwan-news-crawlers
$ pip install -r requirements.txt
$ scrapy crawl apple -o apple_news.json
```

## Prerequisites

- Python3
- Scrapy 2.13.3

## Usage
```scrapy crawl <spider> -o <output_name>```
### Available spiders
1. apple
2. appleRealtime
3. china
4. cna
5. cts
6. ettoday
7. liberty
8. libertyRealtime
9. pts
10. setn
11. tvbs
12. udn

## Output
| Key | Value |
| :---      |          :--- |
| website   | the publisher|
| url       | the origin web|
| title     | the news title|
| content   | the news content      |
| category  | the category of news |

## License
The MIT License
