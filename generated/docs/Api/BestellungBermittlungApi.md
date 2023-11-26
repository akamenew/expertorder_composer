# OpenAPI\Client\BestellungBermittlungApi

All URIs are relative to https://osp.expertorder.de, except if the operation defines another base path.

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
| [**pushPut()**](BestellungBermittlungApi.md#pushPut) | **PUT** /push |  |


## `pushPut()`

```php
pushPut($api_key, $order)
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new OpenAPI\Client\Api\BestellungBermittlungApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_key = 'api_key_example'; // string | Diese Api-Key identifiziert an welche ExpertOrder die Bestellung weiter geleitet werden soll.
$order = {"version":1,"broker":"TestShop.de","fromMobile":false,"clientIp":"192.168.1.2","id":"20221121114617984","oldid":"20221121114617988","ordertime":"2022-11-21T11:46:17.988Z","deliverytime":"2022-11-21T11:46:17.988Z","customerinfo":"Quittung nicht vergessen","orderprice":20.5,"orderdiscount":0.0,"bonuscard":"","notification":false,"deliverycost":0.0,"tip":0.0,"customer":{"phone":"01700000001","email":"test@test.de","companyname":"RevoutIT","departmentname":"ExpertOrder","name":"Revout","street":"Ing.-Honnef-Str. 13","zip":"21509","location":"Glinde","addressinfo":"1.OG"},"payment":{"type":1,"provider":"","transactionid":"","prepaid":0.0},"items":[{"count":1,"name":"Menü 1","price":17.0,"items":[{"count":1,"name":"Sommer-Salat standard","price":0.0,"items":[{"count":1,"name":"French Dressing","price":0.0,"items":[]},{"count":1,"name":"Brötchen zum Salat standard","price":0.0,"items":[]}]},{"count":1,"name":"Pizza Vegetaria small","price":0.0,"items":[]},{"count":1,"name":"Warme Pfannkuchen","price":0.0,"items":[{"count":1,"name":"mit heißen Kirschen und Vanille-Sauce","price":0.0,"items":[]}]}]},{"count":1,"name":"Coca Cola 1l","price":3.5,"items":[]}]}; // \OpenAPI\Client\Model\Order

try {
    $apiInstance->pushPut($api_key, $order);
} catch (Exception $e) {
    echo 'Exception when calling BestellungBermittlungApi->pushPut: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **api_key** | **string**| Diese Api-Key identifiziert an welche ExpertOrder die Bestellung weiter geleitet werden soll. | |
| **order** | [**\OpenAPI\Client\Model\Order**](../Model/Order.md)|  | |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)
