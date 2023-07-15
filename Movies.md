---
cssclass: cards, cards-cover, cards-2-3, table-max
---
```dataview
TABLE without id ("![]("+ poster + ")") as Poster, file.link as Name, "" + year as Year, "by " + director as Director, "Score: " + scoreImdb as Score, genre as Genres, "Length: " + length as Length, cast as Cast, rating as Rating, watchlist as Watchlist from "Movies"
WHERE poster != null
SORT file.name asc
```

---
References: 
- https://en.wikipedia.org/wiki/Lists_of_Universal_Pictures_films
- https://en.wikipedia.org/wiki/List_of_Pixar_films
- https://en.wikipedia.org/wiki/List_of_Walt_Disney_Pictures_films
- https://en.wikipedia.org/wiki/Lists_of_Warner_Bros._films
- https://en.wikipedia.org/wiki/Lists_of_Columbia_Pictures_films
- https://en.wikipedia.org/wiki/Lists_of_Paramount_Pictures_films
- https://en.wikipedia.org/wiki/List_of_Sony_Pictures_Animation_productions
- https://en.wikipedia.org/wiki/List_of_Marvel_Cinematic_Universe_films