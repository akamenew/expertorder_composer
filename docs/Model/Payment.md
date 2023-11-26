# # Payment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **int** | 0 - Barzahlung&lt;br&gt; 1 - EC mit PIN vor Ort&lt;br&gt; 3 - Onlinezahlung&lt;br&gt; |
**provider** | **string** | Die Firma, die für das Bezahlen verantwirtlich ist. z.B. PayPal. Erforderlich, wenn type&#x3D;3 ist. Onlinezahlung. | [optional]
**transactionid** | **string** | Die ID der Bezahl-Transaction. Erforderlich, wenn type&#x3D;3 ist. Onlinezahlung. | [optional]
**prepaid** | **float** | Die Summe, die tatsächlich online Bezahlt wurde. Erforderlich, wenn type&#x3D;3 ist. Onlinezahlung. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
