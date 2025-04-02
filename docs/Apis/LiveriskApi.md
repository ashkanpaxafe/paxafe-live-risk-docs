# LiveriskApi

All URIs are relative to *https://api.paxafe.com/live-risk/v2*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**getLiveRisk**](LiveriskApi.md#getLiveRisk) | **POST** /getLiveStatus | PAXAFE Live Risk API v2 |


<a name="getLiveRisk"></a>
# **getLiveRisk**
> LiveRiskResponse getLiveRisk(getLiveRisk\_request)

PAXAFE Live Risk API v2

    **Monitoring Simplified. Prevent product waste &amp; ensure on-time delivery.** Unlock loss prevention, Reduce monitoring burden, and build the foundation for scaling IoT.  Live Risk recommends Act, Watch or Ignore for each shipment and applied at each shipments&#39; device ping.  API response Includes specific risk factors and contextual risk summary statement.  Multiple risk factors evaluated including Predicted Time of Arrival (PTA), Predicted Temperature Excursion (PTE), internal SLA&#39;s/contracts and external risk factors (weather, traffic, geopolitical)

### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **getLiveRisk\_request** | [**getLiveRisk_request**](../Models/getLiveRisk_request.md)|  | [optional] |

### Return type

[**LiveRiskResponse**](../Models/LiveRiskResponse.md)

### Authorization

[x-api-key](../README.md#x-api-key)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

