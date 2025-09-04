##### **The data cleaning process on was performed through Google Sheets**



###### 1\. *Date Column*

* Left blanks as it is since missing dates did not make any impact on the funding analysis.



###### 2\. *Amount Column*



* Commas, hyphens, and other punctuation were removed.
* Converted column to numeric (currency).
* Replaced blanks with 0 for calculation purpose.
* Added a new column Amount\_Status to distinguish Known vs Unspecified funding values.
* Replaced the Blank cells with "Unspecified" entries to produce clearity.



###### 3\. *Investment Type Column*



* Fixed misspellings and inconsistencies.

* Combined duplicate occurrences that are the same idea (e.g., Angel Funding, Angel Round → Angel).

* Introduced regular naming conventions to establish the same categories.
* Replaced the Blank cells with "Unspecified" entries to produce clearity.



###### 4\. *Location Column*

* Several significant revisions occurred for improved geographic alignment:

&nbsp;    a) Entries such as "Mumbai/USA" simplified to Mumbai in order to exclude mapping errors and maintain the spotlight on India.

&nbsp;    b) Commodity-level entries such as "India" are substituted with Bengaluru (the most frequent city in the data set), so all records will be mappable. c) Multi-location entries (e.g.,         	“Bengaluru/Mumbai”) were resolved using two rules:

* Used the official HQ city if available.
* Otherwise, applied a “first city listed” rule (e.g., “Bengaluru/Mumbai” → Bengaluru).
* Replaced the Blank cells with "Unspecified" entries to produce clearity.



