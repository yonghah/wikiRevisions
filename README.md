# wikiRevisions
get revision history of Wikipedia pages 

## Usage

input: titles of page, language of wikipedia

> df <- wikiRevisions(c("Bucheon", "Goyang"),"en")

returns dataset with date, date_posix, and the tile of page

## dependency

* httr
* dplyr
