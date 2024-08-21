# StoreApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**storeAddStoreUserPost**](StoreApi.md#storeAddStoreUserPost) | **POST** /Store/AddStoreUser |  |
| [**storeDeleteStoreUserDelete**](StoreApi.md#storeDeleteStoreUserDelete) | **DELETE** /Store/DeleteStoreUser |  |
| [**storeEditStorePost**](StoreApi.md#storeEditStorePost) | **POST** /Store/EditStore |  |
| [**storeGetStoreUserByIdGet**](StoreApi.md#storeGetStoreUserByIdGet) | **GET** /Store/GetStoreUserById |  |
| [**storeGetStoreUserChangeLogListGet**](StoreApi.md#storeGetStoreUserChangeLogListGet) | **GET** /Store/GetStoreUserChangeLogList |  |
| [**storeGetStoreUserListGet**](StoreApi.md#storeGetStoreUserListGet) | **GET** /Store/GetStoreUserList |  |
| [**storeGetStoresByBrandIdGet**](StoreApi.md#storeGetStoresByBrandIdGet) | **GET** /Store/GetStoresByBrandId |  |


<a name="storeAddStoreUserPost"></a>
# **storeAddStoreUserPost**
> storeAddStoreUserPost(logginUid, StoreUserEditModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **logginUid** | **String**|  | [optional] [default to null] |
| **StoreUserEditModel** | [**StoreUserEditModel**](../Models/StoreUserEditModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="storeDeleteStoreUserDelete"></a>
# **storeDeleteStoreUserDelete**
> storeDeleteStoreUserDelete(userId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **userId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="storeEditStorePost"></a>
# **storeEditStorePost**
> storeEditStorePost(editUid, logginUid, StoreUserEditModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **editUid** | **String**|  | [optional] [default to null] |
| **logginUid** | **String**|  | [optional] [default to null] |
| **StoreUserEditModel** | [**StoreUserEditModel**](../Models/StoreUserEditModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="storeGetStoreUserByIdGet"></a>
# **storeGetStoreUserByIdGet**
> storeGetStoreUserByIdGet(userId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **userId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="storeGetStoreUserChangeLogListGet"></a>
# **storeGetStoreUserChangeLogListGet**
> storeGetStoreUserChangeLogListGet(userId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **userId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="storeGetStoreUserListGet"></a>
# **storeGetStoreUserListGet**
> storeGetStoreUserListGet(storeId)



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

<a name="storeGetStoresByBrandIdGet"></a>
# **storeGetStoresByBrandIdGet**
> storeGetStoresByBrandIdGet(brandId)



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

