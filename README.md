# Cache - Soccer Data

A cache for datasets from James P. Curley's Soccer Data R statistics package.


## What's James P. Curley's Soccer Data?


...



## Why Cache the Datasets?

### What's unchanged?

The club names get copied as is incl. typos.


### What's changed?

The league codes (`1`, `2`, `3`, `4`, ...) get changed to
the football.db "standard" using two letter ISO codes for countries
and if no ISO code exists (e.g. for England, Scotland) than the three letter FIFA codes for countries (e.g. ENG, SCO) get used.

The datasets here use the football.csv "standard", that is, one datafile
per season and league. The league code becomes the file name and the season the
directory name e.g. `1958-59/eng.1.csv` or `1958-59/eng.3n.csv`





## Questions? Comments?

Send them along to the
[Open Sports & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!
