

## Highlights

* Faster and more secure database access using prepared statements (#1593)
* Improved formula for calculating skill losses - Schum's formula (#1661)
* fix team spirit influence on midfield rating (#1778)
* login dialog shows team logos (#1643)

## [Detailed Changelog](https://github.com/akasolace/HO/issues?q=milestone%3A7.0)

### Database
* faster and more secure database access using prepared statements (#1593)
* refactoring of user administration (#1628)
* each HO process uses its own log file (#1800)

### Squad
* add last match columns: rating at end of match, position and minutes (#1523)
* add mother club and matches current team columns (#1401)
* fix `ArrayIndexOutOfBoundsException` upon startup, as no column could be displayed (#1757)
* fix player compare when sold player is bought back again (#1624)
* new column HTMS-28, player potential (#1288)
* fix last match date of walkover matches (#1776)
* fix npe when player avatar download fails (#1806)
* fix best position display in skill tester (#1822)
* fix import of hrf files from portal tracker (#1829)

### Team Analyzer
* team analyzer displays man marking tactic (#1741)
* add opponents' team development numbers to recap table (#347)
* adjust panel layouts for font size 16 (#1805)

### Rating
* fix team spirit influence on midfield rating (#1778)

### Matches
* reload of match details supports selection ranges (#1595)

### Lineup
* SubstitutionEditor shows effect on loddarstats (#1626)
* fix bug of cleared next lineup when wrong matches were downloaded from HT (#1721)
* lineup rating pane is scrollable (#1783)
* fix error in lineup position panel (#1795)

### Statistics
* add tooltips and labels to series data points (#1199)
* player statistics no longer shows players that quit the club before selected time range (#1705)

### Transfer
* display player's age at transfer date (#1659)
* Transfer module is no longer an autostart module to speed up the first download (#1760)

### Training
* fix daylight saving resetting future trainings (#1668)
* fix skill drop calculation - use Schum's formula (#1661)
* fix error in training calculation due to incorrectly loaded cup matches (#1714)
* changing training priorities in prediction table will update player details views (#1798)

### League
* fix order of last 5 matches - use the same as hattrick (#1793)
* disable league promotion feature (#1412)

### Youth
* duration format d hh:mm:ss of "can be promoted in" when less than one day is left (#1578)

### Misc
* fix display of wrong currency and character encoding when ht worldetails table wasn't initialized (#1622)

## Translations

Reports by Contributors - October 15, 2022 - February 04, 2023

* Jan 131
* sich 16
* wsbrenk 16
* Lidegand 14
* Moorhuhninho 13
* TeamBMW 5

Total 195