# getLiveRisk_request
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **shipment\_id** | **String** | Unique identifier for the shipment | [default to null] |
| **device\_time** | **Long** | Device timestamp in epoch time | [default to null] |
| **device\_id** | **String** | Unique identifier for the device | [optional] [default to null] |
| **latitude** | **Float** | Latitude of the current location. If missing, only temperature_impact will be present in the output response. | [optional] [default to null] |
| **longitude** | **Float** | Longitude of the current location. If missing, only temperature_impact will be present in the output response. | [optional] [default to null] |
| **temperature** | **Float** | Current temperature in Celsius. If missing, only delivery_impact and external_impact will be present in the output response. | [optional] [default to null] |
| **battery** | **Float** | Current battery in percentage. If missing, only delivery_impact, external_impact and temperature_impact will be present in the output response. | [optional] [default to null] |
| **lane\_id** | **String** | Lane identifier or name. | [optional] [default to null] |
| **customer\_lane\_id** | **String** | Customer lane ID can be input as an alternative for lane_id. | [optional] [default to null] |
| **temperature\_profile** | [**List**](getLiveRisk_request_temperature_profile_inner.md) | Temperature profile data. List of dictionaries with temperature range information.  Not mandatory if temperature is missing. | [optional] [default to null] |
| **contracted\_delivery\_time** | **Integer** | Contracted transit time in minutes. | [optional] [default to null] |
| **delivery\_date** | **Date** | Delivery date and time in UTC. | [optional] [default to null] |
| **journey\_config** | [**List**](getLiveRisk_request_journey_config_inner.md) |  | [optional] [default to null] |
| **shipment\_config** | [**getLiveRisk_request_shipment_config**](getLiveRisk_request_shipment_config.md) |  | [optional] [default to null] |
| **device\_config** | [**getLiveRisk_request_device_config**](getLiveRisk_request_device_config.md) |  | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

