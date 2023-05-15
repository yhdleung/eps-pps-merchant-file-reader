
# EPS PPS Merchant File Reader

Transforms the `PPS Merchant Files` retrieved from `EPS System` to a human readable format.


## Description

This simple reader utility tool aims to provide a convenient way for manual checking and handling of the Merchant File data.
The transformation format is referencing `Appendix B PPS Merchant Reconciliation File` in `EPS System - Appendix for Merchant File Download Service (PPS)` Version 2.1 prepared by EPS Project team.


## Assumption

- The data file is relatively small (e.g. <300 MB), which can be handled entirely on client browser.
- The terminal header/trailer records without any transaction details are considered not useful and would be ignored.


## Road map

- [x] read and collect data into JSON
- [x] print data into HTML table
- [x] load multiple files
- [x] revise format
- [x] export data to CSV


## License

[MIT](https://choosealicense.com/licenses/mit/)