{
  "info": {
    "name": "Clarity Accounting Get Currencies",
    "_postman_id": "177fb06e-35d2-4bc7-b739-e2f49d36c11d",
    "description": "Get currencies.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Currencies",
      "item": [
        {
          "id": "58634158-b27a-4235-b7bc-670b580245c0",
          "name": "getCurrencies",
          "request": {
            "url": "http://api.xero.com/api.xro/2.0/Currencies?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get currencies."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f64932fe-0963-4617-8a3e-de984de52fde"
            }
          ]
        }
      ]
    }
  ]
}