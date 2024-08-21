# StoreInfoApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**storeStoreInfoAddStoreEPaymentPost**](StoreInfoApi.md#storeStoreInfoAddStoreEPaymentPost) | **POST** /store/StoreInfo/AddStoreEPayment |  |
| [**storeStoreInfoEditStoreEPaymentPost**](StoreInfoApi.md#storeStoreInfoEditStoreEPaymentPost) | **POST** /store/StoreInfo/EditStoreEPayment |  |
| [**storeStoreInfoEditStoreInfoPost**](StoreInfoApi.md#storeStoreInfoEditStoreInfoPost) | **POST** /store/StoreInfo/EditStoreInfo |  |
| [**storeStoreInfoGetEPaymentTypeOptionsGet**](StoreInfoApi.md#storeStoreInfoGetEPaymentTypeOptionsGet) | **GET** /store/StoreInfo/GetEPaymentTypeOptions |  |
| [**storeStoreInfoGetStoreEPaymentInfoGet**](StoreInfoApi.md#storeStoreInfoGetStoreEPaymentInfoGet) | **GET** /store/StoreInfo/GetStoreEPaymentInfo |  |
| [**storeStoreInfoGetStoreInfoGet**](StoreInfoApi.md#storeStoreInfoGetStoreInfoGet) | **GET** /store/StoreInfo/GetStoreInfo |  |


<a name="storeStoreInfoAddStoreEPaymentPost"></a>
# **storeStoreInfoAddStoreEPaymentPost**
> storeStoreInfoAddStoreEPaymentPost(logginUid, storeId, Id, SecretKey, StoreId, PaymentType, MerchantId, SecretKeyText, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **logginUid** | **String**|  | [optional] [default to null] |
| **storeId** | **String**|  | [optional] [default to null] |
| **Id** | **String**|  | [optional] [default to null] |
| **SecretKey** | **byte[]**|  | [optional] [default to null] |
| **StoreId** | **String**|  | [optional] [default to null] |
| **PaymentType** | **Integer**|  | [optional] [default to null] |
| **MerchantId** | **String**|  | [optional] [default to null] |
| **SecretKeyText** | **String**|  | [optional] [default to null] |
| **CreatedName** | **String**|  | [optional] [default to null] |
| **CreatedDate** | **Date**|  | [optional] [default to null] |
| **CreatedUid** | **String**|  | [optional] [default to null] |
| **UpdateUid** | **String**|  | [optional] [default to null] |
| **UpdateDate** | **Date**|  | [optional] [default to null] |
| **UpdateName** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

<a name="storeStoreInfoEditStoreEPaymentPost"></a>
# **storeStoreInfoEditStoreEPaymentPost**
> storeStoreInfoEditStoreEPaymentPost(logginUid, id, Id, SecretKey, StoreId, PaymentType, MerchantId, SecretKeyText, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **logginUid** | **String**|  | [optional] [default to null] |
| **id** | **String**|  | [optional] [default to null] |
| **Id** | **String**|  | [optional] [default to null] |
| **SecretKey** | **byte[]**|  | [optional] [default to null] |
| **StoreId** | **String**|  | [optional] [default to null] |
| **PaymentType** | **Integer**|  | [optional] [default to null] |
| **MerchantId** | **String**|  | [optional] [default to null] |
| **SecretKeyText** | **String**|  | [optional] [default to null] |
| **CreatedName** | **String**|  | [optional] [default to null] |
| **CreatedDate** | **Date**|  | [optional] [default to null] |
| **CreatedUid** | **String**|  | [optional] [default to null] |
| **UpdateUid** | **String**|  | [optional] [default to null] |
| **UpdateDate** | **Date**|  | [optional] [default to null] |
| **UpdateName** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

<a name="storeStoreInfoEditStoreInfoPost"></a>
# **storeStoreInfoEditStoreInfoPost**
> storeStoreInfoEditStoreInfoPost(logginUid, storeId, StoreName, StorePhone, Address, Latitude, Longitude, StoreId, BrandID, Active, OnlineCheckoutEnabled, AllowProductManagement, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **logginUid** | **String**|  | [optional] [default to null] |
| **storeId** | **String**|  | [optional] [default to null] |
| **StoreName** | **String**|  | [optional] [default to null] |
| **StorePhone** | **String**|  | [optional] [default to null] |
| **Address** | **String**|  | [optional] [default to null] |
| **Latitude** | **Double**|  | [optional] [default to null] |
| **Longitude** | **Double**|  | [optional] [default to null] |
| **StoreId** | **String**|  | [optional] [default to null] |
| **BrandID** | **String**|  | [optional] [default to null] |
| **Active** | **Boolean**|  | [optional] [default to null] |
| **OnlineCheckoutEnabled** | **Boolean**|  | [optional] [default to null] |
| **AllowProductManagement** | **Boolean**|  | [optional] [default to null] |
| **CreatedName** | **String**|  | [optional] [default to null] |
| **CreatedDate** | **Date**|  | [optional] [default to null] |
| **CreatedUid** | **String**|  | [optional] [default to null] |
| **UpdateUid** | **String**|  | [optional] [default to null] |
| **UpdateDate** | **Date**|  | [optional] [default to null] |
| **UpdateName** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

<a name="storeStoreInfoGetEPaymentTypeOptionsGet"></a>
# **storeStoreInfoGetEPaymentTypeOptionsGet**
> storeStoreInfoGetEPaymentTypeOptionsGet()



### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="storeStoreInfoGetStoreEPaymentInfoGet"></a>
# **storeStoreInfoGetStoreEPaymentInfoGet**
> storeStoreInfoGetStoreEPaymentInfoGet(storeId, type)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **storeId** | **String**|  | [optional] [default to null] |
| **type** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="storeStoreInfoGetStoreInfoGet"></a>
# **storeStoreInfoGetStoreInfoGet**
> storeStoreInfoGetStoreInfoGet(storeId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **storeId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

