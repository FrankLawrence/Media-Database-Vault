---
cssclass: cards, cards-cover, cards-2-3, table-max
---
```dataview
TABLE without id ("![]("+ poster + ")") as Poster, file.link as Name, "" + year as Year, "by " + director as Director, "Score: " + scoreImdb as Score, genre as Genres, "Length: " + length as Length, cast as Cast, rating as Rating, watchlist as Watchlist from "Movies"
WHERE poster != null AND watchlist != null
SORT watchlist asc
```