---
title: Minute
description: The minute that the metric occurred on.
---

# Minute

The 'Minute' dimension reports the minute that a given metric occurred (rounded down). The first dimension value is the first minute in the date range, and the last dimension value is the last minute in the date range. This dimension is valuable for trended reports, as it allows you to see metrics over time. Given how granular this dimension is, Adobe recommends limiting the reporting date range to one or two days.

## Populate this dimension with data

This dimension works out of the box for all implementations. If a report suite contains data, this dimension works.

## Dimension values

Dimension values include a given minute within a report's date range alongside its date. It is formatted as `HH:MM YYYY-MM-DD`. Dimension values starting with `00:00` equate to midnight on that day, while values starting with `23:59` equate to 11:59 PM for that day.
