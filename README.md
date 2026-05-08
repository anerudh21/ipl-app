Overview
This project implements a comprehensive Data Engineering and Analysis Pipeline using Python and Pandas. It transforms raw ball-by-ball IPL data into actionable insights, simulating a production-grade workflow: Ingest → Clean → Transform → Analyze → Report → Export.

Pipeline Architecture
Ingestion: Loading deliveries.csv and matches.csv.

Cleaning: Handling missing values, validating data types, and aligning Match IDs.

Transformation: Merging datasets and calculating total runs per delivery (including extras).

Analysis: Executing 20 distinct analytical queries (Strike Rates, Death Over performance, Venue trends, etc.).

Reporting: Formatting results into readable, sorted DataFrames.

Export: Automated generation of CSV files and a multi-sheet Excel summary.
