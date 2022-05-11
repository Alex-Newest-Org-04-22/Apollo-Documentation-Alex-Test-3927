# Internal Campaigns Displayed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "view_promotion",
  "detailed_event": "Internal Campaigns Displayed",
    "ecommerce": {
        "items": [
            {
                "item_id": "<item_id>",
                "item_name": "<item_name>",
                "location_id": "<location_id>"
            }
        ],
        "promotion_id": "<promotion_id>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|ecommerce.items[n].item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\)|SKU\_12345|||||||
|ecommerce.items[n].item_name|string|Item Name \(context-specific\).|jeggings|||||||
|ecommerce.items[n].location_id|string|Captures a unique ID of a physical location such as a store, banking branch, atm, hotel, office, or other.|155, 65588, 987764448|||||||
|ecommerce.promotion_id|unknown|Captures the ID associated with internal campaigns. Used for internal campaign impressions and clicks only.|2345, 56789, 9876|||||||




