# IS107_Case-Studies_DAX-in-Power-BI


1. Answer
   - So the Calculated Column is row-to-row stored in the table, which means it is computed once when the data is loaded or refreshed. Calculated columns were used when we need persistent, row-level data such as categories and keys.
While the measure is calculated on the fly means that it depends on the filter, it also calculated dynamically at query time, not stored in the table. Measures are mainly used for aggregation (sum, average, count), KPI`s and dashboard and also respond to slicer.
So, in overall, all the calculated column is faster at only in query time and it's good for only fixed logic, but its static doesn't react to filters, while in measure it's a lightweight, better for large datasets but slow in visual if it's very complex. But in time of flexibility, it's better to use the measure because they respond to user interaction in reports.

