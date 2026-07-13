---
title: "Searching for Words by Detail Type"
url: "https://blog.wordsapi.com/2015/01/searching-for-words-by-detail-type.html"
date: "2015-01-30"
author: "Unknown"
feed_url: "https://blog.wordsapi.com/feeds/posts/default"
---
We've expanded the Words API search functionality so that you can now search for words that have one or more detail types. For instance, if you wanted to find words that have both "hasUsages" and "hasCategories" relationships, you would call the API like this: https://wordsapiv1.p.mashape.com/words/?hasDetails=hasUsages,hasCategories { "query": { "hasDetails": "hasUsages,hasCategories", "limit": 100, "page": 1 }, "results": { "total": 7, "data": [ "humor", "humour", "trademark", "wit", "witticism", "wittiness", "yiddish" ] } } You can also use this to search for random words, like so: https://
