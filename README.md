## Zürich CarParks Historical data

This repo holds a dump of occupancy status for the parking places in the city of Zürich. 
Data is available as CSV and is stored inside the .zip file of this repo, i.e. `parking-zh-2017-09-13.zip`

## DataSource

The CSV data is derived from regular (each 5') parsing of the [Parkleitsystem Stadt Zürich RSS feed](http://www.plszh.ch/plsFeed/rss)

More info on the data source: https://data.stadt-zuerich.ch/dataset/parkleitsystem

Last update: **13.Sep 2017**

CSV sample:
```
datetime,place_id,status,places_no
.....
"2017-09-13 22:10:03",octavo,open,115
"2017-09-13 22:10:03",opera,open,218
"2017-09-13 22:10:03",p_west,open,355
"2017-09-13 22:10:03",park_hyatt,open,192
"2017-09-13 22:10:03",parkside,open,24
"2017-09-13 22:10:03",pfingstweid,open,203
"2017-09-13 22:10:03",stampfenbach,open,184
"2017-09-13 22:10:03",talgarten,open,84
"2017-09-13 22:10:03",unispital_nord,open,123
"2017-09-13 22:10:03",uni_irchel,error,0
"2017-09-13 22:10:03",urania,open,319
"2017-09-13 22:10:03",utoquai,open,113
"2017-09-13 22:10:03",zueri11,open,49
"2017-09-13 22:10:03",zuerichhorn,open,40
"2017-09-13 22:10:03",bienen,open,29
"2017-09-13 22:10:03",eisfeld,open,44
"2017-09-13 22:10:03",theater_11,open,0
"2017-09-13 22:10:03",unispital_sued,open,74
```

## License

**Copyright (c) 2017 Vasile Coțovanu** - http://www.vasile.ch
 
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the **following conditions:**
 
* **The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.**
 
* THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
