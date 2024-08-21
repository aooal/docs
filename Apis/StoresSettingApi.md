# StoresSettingApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**brandStoresSettingAddStorePost**](StoresSettingApi.md#brandStoresSettingAddStorePost) | **POST** /brand/StoresSetting/AddStore |  |
| [**brandStoresSettingAddStoreUserPost**](StoresSettingApi.md#brandStoresSettingAddStoreUserPost) | **POST** /brand/StoresSetting/AddStoreUser |  |
| [**brandStoresSettingDeleteStoreDelete**](StoresSettingApi.md#brandStoresSettingDeleteStoreDelete) | **DELETE** /brand/StoresSetting/DeleteStore |  |
| [**brandStoresSettingDeleteStoreUserDelete**](StoresSettingApi.md#brandStoresSettingDeleteStoreUserDelete) | **DELETE** /brand/StoresSetting/DeleteStoreUser |  |
| [**brandStoresSettingEditStorePost**](StoresSettingApi.md#brandStoresSettingEditStorePost) | **POST** /brand/StoresSetting/EditStore |  |
| [**brandStoresSettingEditStoreUserPost**](StoresSettingApi.md#brandStoresSettingEditStoreUserPost) | **POST** /brand/StoresSetting/EditStoreUser |  |
| [**brandStoresSettingGetStoreGet**](StoresSettingApi.md#brandStoresSettingGetStoreGet) | **GET** /brand/StoresSetting/GetStore |  |
| [**brandStoresSettingGetStoreLimitGet**](StoresSettingApi.md#brandStoresSettingGetStoreLimitGet) | **GET** /brand/StoresSetting/GetStoreLimit |  |
| [**brandStoresSettingGetStoreUserChangeLogListGet**](StoresSettingApi.md#brandStoresSettingGetStoreUserChangeLogListGet) | **GET** /brand/StoresSetting/GetStoreUserChangeLogList |  |
| [**brandStoresSettingGetStoresListGet**](StoresSettingApi.md#brandStoresSettingGetStoresListGet) | **GET** /brand/StoresSetting/GetStoresList |  |
| [**brandStoresSettingGetStoresUserGet**](StoresSettingApi.md#brandStoresSettingGetStoresUserGet) | **GET** /brand/StoresSetting/GetStoresUser |  |
| [**brandStoresSettingGetStoresUserListGet**](StoresSettingApi.md#brandStoresSettingGetStoresUserListGet) | **GET** /brand/StoresSetting/GetStoresUserList |  |


<a name="brandStoresSettingAddStorePost"></a>
# **brandStoresSettingAddStorePost**
> brandStoresSettingAddStorePost(logginUid, StoresSettingEditModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **logginUid** | **String**|  | [optional] [default to null] |
| **StoresSettingEditModel** | [**StoresSettingEditModel**](../Models/StoresSettingEditModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="brandStoresSettingAddStoreUserPost"></a>
# **brandStoresSettingAddStoreUserPost**
> brandStoresSettingAddStoreUserPost(logginUid, Brand\_StoresUserEditModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **logginUid** | **String**|  | [optional] [default to null] |
| **Brand\_StoresUserEditModel** | [**Brand_StoresUserEditModel**](../Models/Brand_StoresUserEditModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="brandStoresSettingDeleteStoreDelete"></a>
# **brandStoresSettingDeleteStoreDelete**
> brandStoresSettingDeleteStoreDelete(storeId)



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

<a name="brandStoresSettingDeleteStoreUserDelete"></a>
# **brandStoresSettingDeleteStoreUserDelete**
> brandStoresSettingDeleteStoreUserDelete(uid)



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

<a name="brandStoresSettingEditStorePost"></a>
# **brandStoresSettingEditStorePost**
> brandStoresSettingEditStorePost(editStoreId, logginUid, StoresSettingEditModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **editStoreId** | **String**|  | [optional] [default to null] |
| **logginUid** | **String**|  | [optional] [default to null] |
| **StoresSettingEditModel** | [**StoresSettingEditModel**](../Models/StoresSettingEditModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="brandStoresSettingEditStoreUserPost"></a>
# **brandStoresSettingEditStoreUserPost**
> brandStoresSettingEditStoreUserPost(editUid, logginUid, Brand\_StoresUserEditModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **editUid** | **String**|  | [optional] [default to null] |
| **logginUid** | **String**|  | [optional] [default to null] |
| **Brand\_StoresUserEditModel** | [**Brand_StoresUserEditModel**](../Models/Brand_StoresUserEditModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="brandStoresSettingGetStoreGet"></a>
# **brandStoresSettingGetStoreGet**
> brandStoresSettingGetStoreGet(storeId)



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

<a name="brandStoresSettingGetStoreLimitGet"></a>
# **brandStoresSettingGetStoreLimitGet**
> brandStoresSettingGetStoreLimitGet(brandId)



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

<a name="brandStoresSettingGetStoreUserChangeLogListGet"></a>
# **brandStoresSettingGetStoreUserChangeLogListGet**
> brandStoresSettingGetStoreUserChangeLogListGet(userId)



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

<a name="brandStoresSettingGetStoresListGet"></a>
# **brandStoresSettingGetStoresListGet**
> brandStoresSettingGetStoresListGet(brandId)



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

<a name="brandStoresSettingGetStoresUserGet"></a>
# **brandStoresSettingGetStoresUserGet**
> brandStoresSettingGetStoresUserGet(storeId, userId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **storeId** | **String**|  | [optional] [default to null] |
| **userId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="brandStoresSettingGetStoresUserListGet"></a>
# **brandStoresSettingGetStoresUserListGet**
> brandStoresSettingGetStoresUserListGet(storeId)



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

