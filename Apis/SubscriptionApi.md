# SubscriptionApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**adminSubscriptionAddSubscriptionPlanPost**](SubscriptionApi.md#adminSubscriptionAddSubscriptionPlanPost) | **POST** /admin/Subscription/AddSubscriptionPlan |  |
| [**adminSubscriptionDeleteSubscriptionPlanDelete**](SubscriptionApi.md#adminSubscriptionDeleteSubscriptionPlanDelete) | **DELETE** /admin/Subscription/DeleteSubscriptionPlan |  |
| [**adminSubscriptionEditSubscriptionPlanPost**](SubscriptionApi.md#adminSubscriptionEditSubscriptionPlanPost) | **POST** /admin/Subscription/EditSubscriptionPlan |  |
| [**adminSubscriptionGetOrderListGet**](SubscriptionApi.md#adminSubscriptionGetOrderListGet) | **GET** /admin/Subscription/GetOrderList |  |
| [**adminSubscriptionGetOrderPaymentsGet**](SubscriptionApi.md#adminSubscriptionGetOrderPaymentsGet) | **GET** /admin/Subscription/GetOrderPayments |  |
| [**adminSubscriptionGetSubscriptionPlanGet**](SubscriptionApi.md#adminSubscriptionGetSubscriptionPlanGet) | **GET** /admin/Subscription/GetSubscriptionPlan |  |
| [**adminSubscriptionGetSubscriptionPlanListGet**](SubscriptionApi.md#adminSubscriptionGetSubscriptionPlanListGet) | **GET** /admin/Subscription/GetSubscriptionPlanList |  |
| [**adminSubscriptionUploadPlansPicPost**](SubscriptionApi.md#adminSubscriptionUploadPlansPicPost) | **POST** /admin/Subscription/UploadPlansPic |  |
| [**brandSubscriptionGetBrandIdGet**](SubscriptionApi.md#brandSubscriptionGetBrandIdGet) | **GET** /brand/Subscription/GetBrandId |  |
| [**brandSubscriptionGetPaymentDataPost**](SubscriptionApi.md#brandSubscriptionGetPaymentDataPost) | **POST** /brand/Subscription/GetPaymentData |  |
| [**brandSubscriptionGetPlanDetailGet**](SubscriptionApi.md#brandSubscriptionGetPlanDetailGet) | **GET** /brand/Subscription/GetPlanDetail |  |
| [**brandSubscriptionGetPlanListGet**](SubscriptionApi.md#brandSubscriptionGetPlanListGet) | **GET** /brand/Subscription/GetPlanList |  |
| [**brandSubscriptionGetSubscriberNamesGet**](SubscriptionApi.md#brandSubscriptionGetSubscriberNamesGet) | **GET** /brand/Subscription/GetSubscriberNames |  |
| [**brandSubscriptionSetChargeDataPost**](SubscriptionApi.md#brandSubscriptionSetChargeDataPost) | **POST** /brand/Subscription/SetChargeData |  |


<a name="adminSubscriptionAddSubscriptionPlanPost"></a>
# **adminSubscriptionAddSubscriptionPlanPost**
> adminSubscriptionAddSubscriptionPlanPost(logginUid, SubscriptionPlansEditModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **logginUid** | **String**|  | [optional] [default to null] |
| **SubscriptionPlansEditModel** | [**SubscriptionPlansEditModel**](../Models/SubscriptionPlansEditModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="adminSubscriptionDeleteSubscriptionPlanDelete"></a>
# **adminSubscriptionDeleteSubscriptionPlanDelete**
> adminSubscriptionDeleteSubscriptionPlanDelete(pid)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **pid** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="adminSubscriptionEditSubscriptionPlanPost"></a>
# **adminSubscriptionEditSubscriptionPlanPost**
> adminSubscriptionEditSubscriptionPlanPost(editPid, logginUid, SubscriptionPlansEditModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **editPid** | **String**|  | [optional] [default to null] |
| **logginUid** | **String**|  | [optional] [default to null] |
| **SubscriptionPlansEditModel** | [**SubscriptionPlansEditModel**](../Models/SubscriptionPlansEditModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="adminSubscriptionGetOrderListGet"></a>
# **adminSubscriptionGetOrderListGet**
> adminSubscriptionGetOrderListGet()



### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="adminSubscriptionGetOrderPaymentsGet"></a>
# **adminSubscriptionGetOrderPaymentsGet**
> adminSubscriptionGetOrderPaymentsGet(orderId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **orderId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="adminSubscriptionGetSubscriptionPlanGet"></a>
# **adminSubscriptionGetSubscriptionPlanGet**
> adminSubscriptionGetSubscriptionPlanGet(pid)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **pid** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="adminSubscriptionGetSubscriptionPlanListGet"></a>
# **adminSubscriptionGetSubscriptionPlanListGet**
> adminSubscriptionGetSubscriptionPlanListGet()



### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="adminSubscriptionUploadPlansPicPost"></a>
# **adminSubscriptionUploadPlansPicPost**
> adminSubscriptionUploadPlansPicPost(PlansPicFile)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **PlansPicFile** | **File**|  | [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

<a name="brandSubscriptionGetBrandIdGet"></a>
# **brandSubscriptionGetBrandIdGet**
> brandSubscriptionGetBrandIdGet(uid)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **uid** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="brandSubscriptionGetPaymentDataPost"></a>
# **brandSubscriptionGetPaymentDataPost**
> brandSubscriptionGetPaymentDataPost(Period)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **Period** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

<a name="brandSubscriptionGetPlanDetailGet"></a>
# **brandSubscriptionGetPlanDetailGet**
> brandSubscriptionGetPlanDetailGet(pid)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **pid** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="brandSubscriptionGetPlanListGet"></a>
# **brandSubscriptionGetPlanListGet**
> brandSubscriptionGetPlanListGet()



### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="brandSubscriptionGetSubscriberNamesGet"></a>
# **brandSubscriptionGetSubscriberNamesGet**
> brandSubscriptionGetSubscriberNamesGet(brandId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **brandId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="brandSubscriptionSetChargeDataPost"></a>
# **brandSubscriptionSetChargeDataPost**
> brandSubscriptionSetChargeDataPost(SetChargeDataEditModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **SetChargeDataEditModel** | [**SetChargeDataEditModel**](../Models/SetChargeDataEditModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

