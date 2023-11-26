# # Item

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uid** | **string** | Eindeutige ID des Artikels. Wenn gesetzt, dann wird die Zuordnung anhand dieser Nummer gemacht. Optional. | [optional]
**count** | **float** | Anzahl |
**name** | **string** | Artikelname. |
**info** | **string** | Zusätzliche Information zum Artikel. Optional. | [optional]
**price** | **float** |  |
**group** | **string** | Artikelgruppe. z.B. Pizzen, Salate oder Getränke. Wird verwendet, wenn dieser Artikel automatisch zur Speisekarte hinzugefügt werden soll. Optional. | [optional]
**type** | **string** | Gibt an, ob dieser Artikel Essen oder kein Essen ist. Relevant für MwSt.-Bestimmung. Wird verwendet, wenn dieser Artikel automatisch zur Speisekarte hinzugefügt werden soll. Optional. | [optional]
**items** | [**\OpenAPI\Client\Model\Item[]**](Item.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
