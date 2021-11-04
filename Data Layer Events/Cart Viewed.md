# Cart Viewed

### 

## Javascript Code
```js
window.appEventData1104 = window.appEventData1104 || [];
appEventData1104.push({
  "event": "Cart Viewed",
    "cart": {
        "cartID": "<cartID>",
        "item": [
            {
                "price": {
                    "isHidden": <isHidden>,
                    "priceTier": "<priceTier>"
                },
                "productInfo": {
                    "brand": "<brand>",
                    "color": "<color>",
                    "isBackOrdered": <isBackOrdered>,
                    "isOutOfStock": <isOutOfStock>,
                    "name": "<name>",
                    "productID": "<productID>",
                    "productLine": "<productLine>"
                }
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|brand|string|Describes the brand of a product or offering.|Ford, Chevrolet, Dodge, Levis, Columbia, Patagonia|||||||
|cartID|string|Back-end identifier for a shopping cart|12345, 435678, 34567, XCV456, XCV876|||||||
|color|string|Describes the colorway of a product or product variant|Antique Oak, Granite, Black Marble, Knotty Pine|||||||
|isBackOrdered|boolean|Boolean flag indicating that an inventoried product is on backorder|TRUE, FALSE|||||||
|isHidden|integer|Count of times the price of a product was hidden in the cart due to MAP \(Minimum Advertised Pricing\) requirements.
  Set in the product string for only those products where it is applicable, with a value of 1||||||||
|isOutOfStock|integer|Count of times a product was out of stock at the time of cart view.||||||||
|name|string|Name of the product or offering.  Should be unique and 1:1 with productID|Oceana, Corsica, Flame Tech, Air Jordan 88|||||||
|priceTier|string|Describes the general pricing tier of a product. \(Good, Better, Best\)|Good, Better, Best, Bronze, Silver, Gold|||||||
|productID|string|Unique Identifier of a product or offering.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level above SKU for products with SKU variants. |155, 65588, 987764448|||||||
|productLine|string|Describes the product Line of a product. |Laminate Wood, Vinyl, Hardwood, Stone, Ceramic|||||||




