# plumber-data
Data repository for plumber (primarily for tests)


plumber-data is meant to be accessed via a submodule of the main [plumber](https://github.com/ARDG-NRAO/plumber) repository. It exists only to contain large(ish) data necessary to run the unit tests in plumber.


### CSV Files

The CSV files within the csv/ directory can be used by plumber to generate the
leakage beams. The status of the CSV files are summarized in the table below.
While all the CSV files produce morphologically accurate beams, the beams that
have not been verified should be used on a "shared risk" basis.

|Telescope          | Status                                     |
|-------------------|--------------------------------------------|
| EVLA S Band       | :heavy_check_mark: Verified                |
| EVLA L Band       | :x: Unverified                             |
| MeerKAT L Band    | :white_check_mark: Undergoing verification |
| ALMA  DA          | :x: Unverified                             |
| ALMA  DV          | :x: Unverified                             |
