# JavaScript Object Notation

<p align="center"><img src="https://github.com/kwaldenphd/python-structured-data/blob/main/images/JSONSample.jpg?raw=true" width="500"></p>

JavaScript Object Notation (JSON) is another popular way to format data as a single (purportedly human-readable) string. JavaScript programs use JSON data structures, but we can frequently encounter JSON data outside of a JavaScript environment.
'
Websites that make machine-readable data available via an application programming interface.

JSON structures can vary WIDELY depending on the specific data provider, but this lab will cover some basic elements of working with JSON in Python. The easiest way to think of JSON data as a plain-text data format made up of something like key-value pairs, like we've encountered previously in working with dictionaries (as a type of associative array).

Example JSON string: `stringOfJsonData = '{"name": Zophie", "isCat": true, "miceCaught": 0, "felineIQ": null}'`. From looking at the example string, we can see field names or keys (`name`, `isCat`, `miceCaught`, `felineIQ`) and values for those fields.

To use more precise terminology, JSON data has the following attributes:
- uses name/value pairs
- separates data using commas

## JSON vs. CSV

How is data stored in a JSON format different than a `.csv`?
- A `.csv` file uses characters as delimiters and has more of a tabular (table-like) structure.
- `.json` data uses characters as part of the syntax, but not in the same way as delimited data files.
- The data stored in a JSON format has values that are attached to names (or keys).
- JSON can also have a hierarchical or nested structure (which is often hard to recreate or represent in a CSV format)

## JSON Example

For example, take a look at sample JSON data from Twitter's API:

```JSON
{
  "created_at": "Thu Apr 06 15:24:15 +0000 2017",
  "id_str": "850006245121695744",
  "text": "1\/ Today we\u2019re sharing our vision for the future of the Twitter API platform!\nhttps:\/\/t.co\/XweGngmxlP",
  "user": {
    "id": 2244994945,
    "name": "Twitter Dev",
    "screen_name": "TwitterDev",
    "location": "Internet",
    "url": "https:\/\/dev.twitter.com\/",
    "description": "Your official source for Twitter Platform news, updates & events. Need technical help? Visit https:\/\/twittercommunity.com\/ \u2328\ufe0f #TapIntoTwitter"
  },
  "place": {   
  },
  "entities": {
    "hashtags": [      
    ],
    "urls": [
      {
        "url": "https:\/\/t.co\/XweGngmxlP",
        "unwound": {
          "url": "https:\/\/cards.twitter.com\/cards\/18ce53wgo4h\/3xo1c",
          "title": "Building the Future of the Twitter API Platform"
        }
      }
    ],
    "user_mentions": [     
    ]
  }
}
```

Even if you don't understanding everything in this JSON string, we can start to identify specific data fields (users, mentions, etc) as well as a hierarchical nesting structure.

## JSON & Python

Python's `json` module is a useful resource for working with this data structure ([link to more detailed tutorial](https://github.com/kwaldenphd/python-structured-data/tree/main#javascript-object-notation)).