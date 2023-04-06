---
hide:
  - toc
---

# Date Range

| Label                 | Date Range |
|:----------------------|:-----------|
| URI                   | `gbl_dateRange_drsim` |
| Obligation            | Optional |
| Multivalued           | true |
| Field type            | string |
| Purpose               | To power other time widgets that use a date range |
| Entry Guidelines      | Enter a start date and end date in the [Solr date range](https://solr.apache.org/guide/8_3/working-with-dates.html#date-range-formatting) field convention. In JSON, the value should be formatted as a string that includes the brackets, rather than as an array or list containing a string. Incorrect: ["YYYY TO YYYY"] - Correct: "[YYYY TO YYYY]" |
| Commentary            | This field is not yet supported by GeoBlacklight, but the application can be customized to use it. |
| Controlled Vocabulary | no |
| Example value         | `"[1980 TO 1995]"` |
| Element Set           | GBL |
| Group                 | Temporal |