# Methodology

## 1. Business question

Which products and channels drive Nestlé R&D Australia's sales revenue, how has revenue grown over time, and are there seasonal patterns worth planning around?

## 2. Data source

Not independently verifiable. The dashboard is a view-only Power BI report referencing a Nestlé R&D Australia branded product dataset; the underlying dataset's real-world origin (actual company data vs. a public/case-study dataset) is not exposed through the public link and is not claimed here as a verified client engagement.

## 3. Data preparation

Not accessible from the public report.

## 4. Data modelling

Not accessible. The report appears to model sales with dimensions for product name, sales channel (Direct/Online), and date (year and month), but the underlying table structure cannot be confirmed without the .pbix file.

## 5. KPI definitions

- **Total sales revenue**: sum of sales value across the dataset.
- **Average sales value**: mean value per recorded sale.
- **Sales by product**: revenue summed per product name.
- **Annual revenue**: revenue summed per calendar year (2018–2020 shown).
- **Channel split**: revenue summed per channel (Direct, Online), expressed as a percentage of total.
- **Monthly sales**: revenue summed per calendar month, aggregated across years shown.

## 6. Analysis

Analysis compares product-level revenue to identify top and bottom performers, tracks year-over-year revenue to assess growth, splits revenue by channel to assess distribution reliance, and aggregates by month to surface seasonality.

## 7. Dashboard design

The published report presents summary KPI cards (total sales, average sale value) alongside product, channel, annual, and monthly breakdowns.

## 8. Validation

No independent validation was possible; figures in this repository are taken directly from the published dashboard as viewed.

## 9. Limitations

- Data provenance is not confirmed; treated as portfolio/practice data.
- The .pbix file and its DAX/Power Query logic are not available for review.
- Findings are based on a single review of the published report, not a refreshed or monitored data feed.
