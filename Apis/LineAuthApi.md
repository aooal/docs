# LineAuthApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**lineCheckLineUserIDGet**](LineAuthApi.md#lineCheckLineUserIDGet) | **GET** /Line/CheckLineUserID |  |
| [**lineLineCertificationGet**](LineAuthApi.md#lineLineCertificationGet) | **GET** /Line/LineCertification |  |
| [**lineLoginGetLineUserDataPost**](LineAuthApi.md#lineLoginGetLineUserDataPost) | **POST** /LineLogin/GetLineUserData |  |
| [**lineLoginLoginUrlGet**](LineAuthApi.md#lineLoginLoginUrlGet) | **GET** /LineLogin/LoginUrl |  |
| [**lineSaveLineUserPost**](LineAuthApi.md#lineSaveLineUserPost) | **POST** /Line/SaveLineUser |  |


<a name="lineCheckLineUserIDGet"></a>
# **lineCheckLineUserIDGet**
> lineCheckLineUserIDGet(lineUserId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **lineUserId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="lineLineCertificationGet"></a>
# **lineLineCertificationGet**
> lineLineCertificationGet(UserId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **UserId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="lineLoginGetLineUserDataPost"></a>
# **lineLoginGetLineUserDataPost**
> lineLoginGetLineUserDataPost(Code, Redirect\_uri)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **Code** | **String**|  | [optional] [default to null] |
| **Redirect\_uri** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="lineLoginLoginUrlGet"></a>
# **lineLoginLoginUrlGet**
> lineLoginLoginUrlGet(paramUrl)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **paramUrl** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="lineSaveLineUserPost"></a>
# **lineSaveLineUserPost**
> lineSaveLineUserPost(LineEditModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **LineEditModel** | [**LineEditModel**](../Models/LineEditModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

