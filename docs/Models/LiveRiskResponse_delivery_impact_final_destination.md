# LiveRiskResponse_delivery_impact_final_destination
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **contracted\_delivery\_time** | **Date** | Final destination time based on the time the shipment began and the contracted transit time | [optional] [default to null] |
| **shipment\_transit\_time** | **Float** | Actual transit time to final destination in minutes | [optional] [default to null] |
| **pta** | **String** | Predicted Time of Arrival at final destination. Available only for onboarded lanes. | [optional] [default to null] |
| **delayed** | **Boolean** | Whether arrival at final destination is delayed | [optional] [default to null] |
| **delayed\_by** | **Integer** | Duration of delay at final destination in minutes, if any | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

