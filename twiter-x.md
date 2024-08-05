# Twitter Search Cheat Sheet

This cheat sheet helps you efficiently search Twitter using specific parameters. Use these queries to find tweets from specific accounts, within certain dates, containing specific phrases, and more.

## Basic Search Queries

| **Search Task**                                  | **Query**                             |
|--------------------------------------------------|---------------------------------------|
| Find tweets from a specific account              | `from:jack`                           |
| Find direct replies to an account                | `to:Snowden`                          |
| Find all tweets mentioning an account            | `@elonmusk`                           |
| Find tweets before a specific date               | `until:2022-12-31`                    |
| Find tweets after a specific date                | `since:2023-01-01`                    |
| Find tweets containing an exact phrase           | `"data breach"`                       |
| Find tweets containing all of a set of terms     | `cybersecurity threat analysis`       |
| Find tweets containing any of a set of terms     | `phishing OR malware OR ransomware`   |
| Find tweets linking to a specific website        | `url:bbc.com`                         |
| Find tweets excluding a specific term            | `from:nasa -launch`                   |
| Find tweets containing images or video           | `hack filter:media`                   |
| Find tweets containing images                    | `cyberattack filter:images`           |
| Find tweets in a specific language               | `data breach lang:en`                 |

## Advanced Search Queries

| **Search Task**                                  | **Query**                             |
|--------------------------------------------------|---------------------------------------|
| Find tweets from a specific account mentioning a term  | `from:JohnDoe hacking`           |
| Find tweets from a specific account containing an exact phrase | `from:JaneSmith "zero-day exploit"` |
| Find tweets that are part of a thread (self-replies)    | `from:securityexpert to:securityexpert` |
| Find tweets from a specific account within a date range | `from:malwarehunter since:2022-01-01 until:2022-12-31` |
| Find tweets from a specific account tagging another account | `from:cybernews @threatintel`       |
| Find tweets linking to a specific website containing a given search term | `url:nytimes.com cybersecurity`     |

## Pentesting and Cybersecurity Specific Queries

| **Search Task**                                  | **Query**                             |
|--------------------------------------------------|---------------------------------------|
| Find tweets about penetration testing tools      | `pentesting tool`                     |
| Find tweets about specific exploits              | `exploit CVE-2023-1234`               |
| Find tweets discussing vulnerability assessments | `vulnerability assessment`            |
| Find tweets mentioning specific hacking groups   | `APT29`                               |
| Find tweets about recent data breaches           | `recent data breach`                  |

## News Specific Queries

| **Search Task**                                  | **Query**                             |
|--------------------------------------------------|---------------------------------------|
| Find tweets linking to a specific news website   | `url:cnn.com`                         |
| Find tweets mentioning breaking news             | `breaking news`                       |
| Find tweets about global events                  | `global event`                        |
| Find tweets from news accounts                   | `from:BBCBreaking`                    |
| Find tweets about recent discoveries             | `recent discovery`                    |

---

## Tips
- Combine multiple queries to narrow down results.
- Use OR to search for any of a set of terms.
- Use exact phrases with quotes for precise searches.
- Filter by media type to find tweets with images or videos.

### Example Combined Queries
- Find tweets from a specific account mentioning any of a set of terms: `from:cybersecnews hacking OR breach OR malware`
- Find tweets from a specific account containing an exact phrase: `from:SecurityDaily "phishing campaign"`
- Find tweets from a specific account within a date range: `from:InfoSec since:2023-01-01 until:2023-07-31`

