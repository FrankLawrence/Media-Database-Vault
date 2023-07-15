---
cssclass: cards, cards-cover, cards-2-3, table-max
---
# Movies
```dataview
TABLE without id ("![]("+ poster + ")") as Poster, file.link as Name, "" + year as Year, "by " + director as Director, "Score: " + scoreImdb as Score, genre as Genres, "Length: " + length as Length, cast as Cast, rating as Rating, watchlist as Watchlist from "Movies"
WHERE poster != null AND contains(genre, [[Drama]])
SORT file.name asc
```
# Series
```dataview
TABLE without id ("![]("+ poster + ")") as Poster, file.link as Name, "" + year as Year, "by " + director as Director, "Score: " + scoreImdb as Score, genre as Genres, "Length: " + length as Length, cast as Cast, rating as Rating, watchlist as Watchlist from "Series"
WHERE poster != null AND contains(genre, [[Drama]])
SORT file.name asc
```