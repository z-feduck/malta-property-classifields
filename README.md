## Malta Property Classifields Analysis

# Preliminary report

The data consists of 275 HTML files. Each file is a saved Property CLassifields page from Times of Malta webpage. The scraped data spans from April 2015 to November 2021, with an interval of 7 days in most cases. Each page contais information about newly published classifields (in relation to date on which it was saved). The data from 2019 includes only 7 pages, in contrast to ~ 30-60 in other years. Among all files 5 were corrupted, with size of 0 bytes:
- *20170425_prop_for_sale_tom_classifieds.html*
- *20170620_prop_for_sale_tom_classifieds.html*
- *20170704_prop_for_sale_tom_classifieds.html*
- *20170713_prop_for_sale_tom_classifieds.html*
- *20180919_prop_for_sale_tom_classifieds.html*

These files should be deleted.

Since *20191023_prop_for_sale_tom_classifieds.html* file the layout of pages has changed a bit. The dates are now in *h3* tags instead of *h2*. Also names of the classes differs.
On pages, below each date, there is a list of property classifields. Each offer has the same structure: "Property for sale" text, localisation name, brief description of an offer, price and a contact number.
A classifield description usually contains info about what kind of property is this, number of rooms as well as available amenities.

The goal of this project is to analyze real estate market in Malta through years.


