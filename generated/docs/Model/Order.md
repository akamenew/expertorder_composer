# # Order

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**version** | **int** | Format-Version. Aktuell &#x3D; 1 |
**broker** | **string** | Name des OnlineshopsProvider |
**from_mobile** | **bool** | true, wenn der Kunde mit dem Smartphone bestellt hat | [optional]
**client_ip** | **string** | die IP Adresse des Kundens | [optional]
**id** | **string** | OSP-Eindeutige ID der Bestellung |
**oldid** | **string** | Wenn die Bestellung eine Änderung ist, dann steht hier die ID der Bestellung, die geändert werden soll | [optional]
**ordertime** | **\DateTime** | Die Zeit, wann die Bestellung erstellt wurde. Format \&quot;yyyy-MM-dd&#39;T&#39;HH:mm:ss.SSS&#39;Z&#39;\&quot; |
**deliverytime** | **\DateTime** | Die gewünschte Lieferzeit. Wenn die Zeit nicht festgelegt wurde, dann soll diese Zeit gleich der Zeit der Bestellung sein. Format \&quot;yyyy-MM-dd&#39;T&#39;HH:mm:ss.SSS&#39;Z&#39;\&quot; |
**customerinfo** | **string** | Zusätzliche Information des Kundens | [optional]
**orderprice** | **float** | Gesamtpreis der Bestellung |
**orderdiscount** | **float** | Rabatt. Absoluter Betrag. Muss negativ sein. |
**bonuscard** | **string** | Die Nummer der Bonuskarte | [optional]
**notification** | **bool** | Gibt an, ob der Kunde keine Lieferung wünscht, sondern selbst abholen möchte. | [optional]
**deliverycost** | **float** | Lieferkosten | [optional]
**tip** | **float** | Trinkgeld | [optional]
**customer** | [**\OpenAPI\Client\Model\Customer**](Customer.md) |  |
**payment** | [**\OpenAPI\Client\Model\Payment**](Payment.md) |  |
**items** | [**\OpenAPI\Client\Model\Item[]**](Item.md) |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
