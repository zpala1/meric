# Methods and limitations (summary)

- Target: one-month-ahead monthly streamflow forecasting, using information available before the forecast month.
- Four primary gauges and a shared evaluation period (1985–1993); later evaluation uses gauges with longer series (1994 onward).
- A1, A123, and A123_LONG lag configurations; monthly anomalies are calculated using past-training climatology.
- Ridge, Random Forest, XGBoost, and CatBoost compared with persistence; temporal folds maintain chronological ordering.
- Training, test and bootstrap logic must respect the missing 1978 year and Tunca's missing 2014 records.
- Predictive importance of lagged discharge does not demonstrate groundwater storage, soil moisture or causal hydroclimatic mechanisms.
- Local Kırklareli/Tekirdağ climate series have spatial representativeness limitations for transboundary upstream catchments.
- Some tree-model checks used intentionally lightweight configurations; report this in the article.

This file summarizes prior analysis and is not a substitute for the complete manuscript and full parameter logs.
