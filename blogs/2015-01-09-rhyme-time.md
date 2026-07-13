---
title: "Rhyme Time!"
url: "https://blog.wordsapi.com/2015/01/rhyme-time.html"
date: "2015-01-09"
author: "Unknown"
feed_url: "https://blog.wordsapi.com/feeds/posts/default"
---
WordsAPI can now be used to find words that rhyme. Rhymes are not returned as part of a normal GET request of a word , so you must call the Rhymes endpoint to retrieve rhymes of a word. https://www.wordsapi.com/words/:word/rhymes The rhymes result will include an object containing the word you requested, and one or more sub-objects that each contain a list of rhyming words.
