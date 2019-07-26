# nyc-transit-archive

This repo was a brief attempt at building a dataset of historical transit arrival times in New York City using `gtfs-tripify` and the MTA's [GTFS-RT archive](http://web.mta.info/developers/data/archives.html). This project ended in failure when I discovered that there were large swatches of data missing from the archives provided by the MTA. Namely, the `{1, 2, 3, 4, 5, 6}` were completely missing from the two samples I took from the dataset, on Febuary 1, 2019 and on June 1, 2019.

Unfortunately, until a more reliable archival service comes into being, the NYT Upshot [Subway Variability Calculator](https://www.nytimes.com/interactive/2019/07/08/upshot/nyc-subway-variability-calculator.html) is the best we can have (the calculator has some fundamental flaws, but whatever).

As an aside, the ultimate useful expression of this data would be a user-queryable API. I did some design work on this. Not only would it require solving the archival problem, it would also require solving other structural problems that amount to a full-time job.

See also [`gtfs-tripify`](https://github.com/ResidentMario/gtfs-tripify) and [`nyc-transit-archive-old`](https://github.com/ResidentMario/nyc-transit-archive-old).
