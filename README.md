Iowa High School Cross Country Results
================

This repository archives the results of cross country state meets held by the Iowa High School Athletic Association. The purpose of sharing the data here is to provide a standardized, tabular transcription of the various [fixed-width results files historically published by the IHSAA](http://www.iahsaa.org/category/cross-country/).

Data Dictionary
===============

| Field    | Type    | Description                                                                                                   |
|:---------|:--------|:--------------------------------------------------------------------------------------------------------------|
| year     | integer | Calendar year of the race.                                                                                    |
| class    | string  | High school athletics classification, based on enrollment. In ascending order, values are 1A, 2A, 3A, and 4A. |
| position | integer | Finishing position.                                                                                           |
| points   | integer | Points awarded to team for finish. Note that individual competitors do not receive points.                    |
| bib      | integer | Race bib number.                                                                                              |
| name     | string  | Name of competitor.                                                                                           |
| grade    | integer | Grade in school. Values are 9, 10, 11, and 12.                                                                |
| school   | string  | Team or school name.                                                                                          |
| time     | float   | Finishing time, in seconds.                                                                                   |

Contributing
============

If you notice a factual error in the data, please open a pull request with the correction and some discussion about the mistake and your source.
