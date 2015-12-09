### Boston Symphony Orchestra complete performance archive
#### With full composer data

A combination of the BSO performance archive data with detailed information about each composer in the dataset

Each row in the csv data has 23 fields. The following are from the original BSO dataset:

```
Date, 
Season (eg 1889-90), 
Composer name (in form used by BSO), 
Work, 
Soloist / Instrument, 
Conductor,
Orchestra performing, 
Venue of performance, 
City of performance
```

And the following are the added composer-specific fields:

```
Name (in standard form), 
gender (0 = male, 1 = female), 
birth year, birth date, 
death year, death date, 
sexual identity (not known for most; = 0 for composers identifying as heterosexual, 1 for gay, and 2 for bi), 
country of citizenship, 
wikidata ID, Library of Congress authority ID, VIAF ID, 
wikipedia link
```

There is such composer data for the vast majority of performances, however there are still a relatively long tail of less-popular composers who remain unidentified.

I've additionally added a unique "performance id" to each set of pieces performed together in a given day. 

See an overview of the process used to create this dataset [here](https://goo.gl/LOkxGR).

Data originally from the [Boston Symphony Orchestra archives](http://archives.bso.org/) and the [Wikidata project](https://www.wikidata.org/wiki/Wikidata:Main_Page).

Released under CC-BY-NC
