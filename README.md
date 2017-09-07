# InventoryLogicApp

[![Deploy to Azure](https://azuredeploy.net/deploybutton.svg)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fcodingwithsasquatch%2FInventoryLogicApp%2Fmaster%2Ftemplate.json)

This is an HTTP Logic App that calls the Inventory API and then returns information on whether or not each item is in stock.

Request Sample:

{ 
    "user":"bob", 
    "cart": 
    [ 
        { 
            "productId":2, 
            "quantity":2 
        }, 
        { 
            "productId":1, 
            "quantity":3 
        } 
    ], 
    "address": "1 My St, City, OH, 55555" 
} 

## Learn more

<TODO> Documentation
