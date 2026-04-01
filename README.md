# What My Reading Says About Me

A small personal project where I tried applying some basic NLP techniques to my Goodreads quotes to see what themes show up.

Started as “let me just make a word cloud,” and turned into figuring out how messy text data actually is.

## What this does

* Combines my Goodreads **quotes + tags**
* Cleans the text (lowercase, remove punctuation, stopwords, etc.)
* Uses part-of-speech tagging to keep **nouns and adjectives only**
* Counts word frequency
* Generates a word cloud to visualize recurring themes

The goal wasn’t to build anything advanced — just to explore what patterns show up in my own reading.

## Example Output

A word cloud showing the most common concepts/themes across my quotes (e.g. love, power, success, relationships, etc.)

## Tech Used

* R
* `tm` (text cleaning)
* `udpipe` (part-of-speech tagging)
* `wordcloud` (visualization)

## Notes

* This is a personal experiment, not a polished product
* Mostly focused on learning how to clean and process text data
* Turns out the hardest part is removing all the useless words

## How to run

1. Export your Goodreads quotes as CSV
2. Place it in the project folder
3. Run the R script
4. The word cloud will be generated in a plot window

## Why I made this

Was curious if you could take something as unstructured as random quotes and extract something meaningful from it.

Also wanted to try basic NLP without overcomplicating things.
