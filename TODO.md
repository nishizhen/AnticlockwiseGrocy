# Todo List

## Barcode Lookup API for China

- **Task:** Find and integrate a barcode lookup service that is more suitable for the Chinese market.
- **Status:** Paused. Research into available APIs has not yet yielded a suitable, publicly available service. The initial candidate from Yonyou Cloud was found to be discontinued.
- **Next Steps:** Continue researching and evaluating potential barcode lookup APIs for Chinese products. Possible search terms: "商品条码查询API", "ean aPI china", etc. Look into API marketplaces like Aliyun API market or others.

## Chinese Quantity Units

- **Task:** Re-implement the addition of common Chinese quantity units (克, 斤, 公斤, 个, etc.) and their conversions.
- **Status:** To Do. The previous implementation via a one-time database migration (`migrations/0255.sql`) was reverted as requested.
- **Next Steps:** Find a more robust method to add these units. For example, check for their existence on application startup and add them if missing, instead of relying on a migration number.
