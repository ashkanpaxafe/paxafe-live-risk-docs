# LiveRiskResponse_temperature_impact
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **risk\_level** | **String** | Risk level for temperature impact | [optional] [default to null] |
| **current\_temperature** | **Float** | Current temperature of the shipment in Celsius | [optional] [default to null] |
| **mean\_temperature\_at\_location\_historical** | **BigDecimal** | Historical average temperature at the current location in Celsius. Available only for onboarded lanes. | [optional] [default to null] |
| **std\_deviation\_temperature\_at\_location\_historical** | **BigDecimal** | Standard deviation of historical temperature at the current location in Celsius. Available only for onboarded lanes. | [optional] [default to null] |
| **temp\_ranges** | [**Map**](TemperatureRange.md) | Temperature profile data. The number of ranges will depend on the temperature profile specified in the input. | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

