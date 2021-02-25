# Backorder-project

Backorder means order for any good or service which cannot be fulfilled due to lack of resources such as raw materials,production capactity.Total backorders, also known as backlog, may be expressed in terms of units or dollar amount.A backorder can be both a good thing and a bad thing.Consider a company like Apple that recently rolled out several new iphone models.Because the initial supply cannot keep up with the magnitude of demand, Apple is immediately in a backorder situation.

On a positive note,backorders indicate a healthy demand for the product.In the case of Apple,customers are likely to wait for several months to get the latest apple products but apple's competitors doesn't have this luxury.Customers will cancel their orders and go somewhere else. Machine learning can identify patterns related to backorders before customer orders.



DATA _The data comes from dataset: Kaggle’s Can You Predict Product Backorders? _ The data file contains the historical data for the 8 weeks prior to the week we are trying to predict. The data were taken as weekly snapshots at the start of each week. The target (or response) is the went_on_backorder variable. To model and predict the target, we’ll use the other features, which include:

* sku – Random ID for the product
* national_inv – Current inventory level for the part
* lead_time – Transit time for product (if available)
* in_transit_qty – Amount of product in transit from source
* forecast_3_month – Forecast sales for the next 3 months
* forecast_6_month – Forecast sales for the next 6 months
* forecast_9_month – Forecast sales for the next 9 months
* sales_1_month – Sales quantity for the prior 1 month time period
* sales_3_month – Sales quantity for the prior 3 month time period
* sales_6_month – Sales quantity for the prior 6 month time period
* sales_9_month – Sales quantity for the prior 9 month time period
* min_bank – Minimum recommend amount to stock
* potential_issue – Source issue for part identified
* pieces_past_due – Parts overdue from source
* perf_6_month_avg – Source performance for prior 6 month period
* perf_12_month_avg – Source performance for prior 12 month period
* local_bo_qty – Amount of stock orders overdue
* deck_risk – Part risk flag
* oe_constraint – Part risk flag
* ppap_risk – Part risk flag
* stop_auto_buy – Part risk flag
* rev_stop – Part risk flag
* went_on_backorder – Product actually went on backorder. This is the target value.
