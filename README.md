# preprocessing
Handled missing values → Filled numeric columns with their median and categorical columns with their most frequent value (mode).

Removed duplicate rows → Ensured no repeated entries.

Standardized text values → Formatted Education and Marital_Status into title case (e.g., graduation → Graduation).

Converted dates → Changed Dt_Customer into a proper datetime format (day-first style).

Renamed column headers → Made all column names lowercase with underscores (e.g., Year_Birth → year_birth).

Fixed data types → Ensured year_birth is int and income is float.

Saved the cleaned dataset → Output file: marketing_campaign_cleaned.csv.
