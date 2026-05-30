## Indexes For ForScore ##
This page contains indexes specifically for the App **ForScore**

### Format ###
The field locations don't matter as long as they are consistent within a file.   The minimum information needed is:
* Title
* Start Page
* End Page

Many of these files came from other apps.  They have the format:
* Title
* Book PDF Name
* Start Page
* End Page

In most of these, the first line lists the column values used in the file.  You should skip that line with the header offset.

The Book PDF Name is not needed by ForScore.  However, in indexes created, I attempt to use the iGigBook pdf link name.  This makes the correlation a little clearer for those coming over from iGigBook.

### Books vs Index ###
Indexes are for **C** books unless noted.

* 557 Standards	- 557Standards.csv
* Bill Evans Fakebook - billevans.csv
* A Charlie Brown Christmas - cbxmas.csv
* Colorado Cookbook - Colorado.csv
* Digital Standards Songbook (Sher) - DigitalStandardsSongbookC.csv
* 24 Gypsy Jazz Standards - djangoinjune.csv
* Firehouse Jazz Band  - FirehouseJazzBand.csv
* Jazz LTD - JazzLTD.csv
* The Latin Real Book (Sher) - LatinRealBook.csv (better)
* The Latin Real Book (Sher) - LatinRealBkC.csv
* new bob book - New-Bob-Book-C-index.csv - Free downloadable PDF from https://www.jstreetjazz.com/FakeBooks/The_New_Bob_Book.pdf (and possibly other locations) built by Bob Roetker. Visit him at https://bobroetkerjazzguitar.yolasite.com.
* The New Real Book 1 (Bb) (Sher) - newrbk1Bb.csv
* The New Real Book 1 (Sher) - newrbk1C.csv
* The New Real Book 2 (Bb) (Sher) - newrbk2Bb.csv
* The New Real Book 2 (Sher) - newrbk2C.csv
* The New Real Book 3 (Bb) (Sher) - newrbk3Bb.csv
* The New Real Book 3 (Sher) - newrbk3C.csv
* New Digital Real Book (Sher) - nrealbk1d.csv
* Charlie Parker Omnibook (bass clef)- parkeromnibookbc.csv
* Real Book 1 v6 (Bb) (Hal Leonard) - realbk1h_Bb.csv
* Real Book 1 v6 (Hal Leonard) - realbk1h.csv
* Real Book 2 v2 (Bb) (Hal Leonard) - realbk2h_Bb.csv
* Real Book 2 v2 (Hal Leonard) - realbk2h.csv
* Real Book 3 v2 (Bb) (Hal Leonard) - realbk3h_Bb.csv
* Real Book 3 v2 (Hal Leonard) - realbk3h.csv
* Real Book 4 v6 (Hal Leonard) - RealBook4.csv
* Real Book 4 (scanned) - realbk4h.csv (page offset has to be +300 due to pdf wierdness)
* Old Real Book 1 - realbk1.csv
* Old Real Book 2 - realbk2.csv
* Old Real Book 3 - realbk3.csv
* Christmas Real Book - realxmasC.csv
* 101 Sinatra Songs - sinatra101C.csv
* The Standards Real Book (Sher) - standardsrbkC.csv
  * NOTE: This is for a scanned copy with no images
* Thelonious Monk's Compositions - thelmnkcp.csv
* Thelonious Monk Fake Book - thelmnkfb.csv
* Vocal Real Book - VocalRealBook.csv

### Workflow ###

You can load these indexes directly from here into your ForScore app by navigating with a web browser, on your device, to this location.  Then select the index you want.  When it opens, then select the **raw** button.  At this point your device should (iPad at least) offer to "open in ForScore".  Selecting that will load it into your ForScore App, and open the App.

If you are updating the index, you should delete all the previous bookmarks for a given book first.
* Open the Book you want to Index
* bookmarks
* edit
* all (selects all)
* delete
* Confirm on the popup
* done

Now load the index
* bookmarks
* indexes (upper left in popup)
* select the index file for the currently displayed book
* Set the Fields.  In the newer indices the first line lists the field values.  Here is an example:
  * First field is **Title**
  * Third field is **Start Page**
  * Forth field is **End Page**
* Adjust the **Header offset** to account for the first comment line if present.
* Adjust the **Page number offset** until the correct image appears for the Title listed.
* Check a few other pages via the page arrows on the bottom of the page.  The image should match the title.

### Notes ###

* The commonly available pdf for **557 Standards** is missing 10+ pages from the end of the book.  The index have the songs marked as "missing" in the title.



