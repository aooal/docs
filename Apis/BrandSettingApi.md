# BrandSettingApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**brandBrandSettingCreateBrandPost**](BrandSettingApi.md#brandBrandSettingCreateBrandPost) | **POST** /brand/BrandSetting/CreateBrand |  |
| [**brandBrandSettingEditBrandPost**](BrandSettingApi.md#brandBrandSettingEditBrandPost) | **POST** /brand/BrandSetting/EditBrand |  |
| [**brandBrandSettingGetBrandGet**](BrandSettingApi.md#brandBrandSettingGetBrandGet) | **GET** /brand/BrandSetting/GetBrand |  |


<a name="brandBrandSettingCreateBrandPost"></a>
# **brandBrandSettingCreateBrandPost**
> brandBrandSettingCreateBrandPost(logginUid, BrandId, BrandName, BrandDescription, BrandLogoFileUrl, BrandLogoFile, Address, BrandPhone, Active, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **logginUid** | **String**|  | [optional] [default to null] |
| **BrandId** | **String**|  | [optional] [default to null] |
| **BrandName** | **String**|  | [optional] [default to null] |
| **BrandDescription** | **String**|  | [optional] [default to null] |
| **BrandLogoFileUrl** | **String**|  | [optional] [default to null] |
| **BrandLogoFile** | **File**|  | [optional] [default to null] |
| **Address** | **String**|  | [optional] [default to null] |
| **BrandPhone** | **String**|  | [optional] [default to null] |
| **Active** | **Boolean**|  | [optional] [default to null] |
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

<a name="brandBrandSettingEditBrandPost"></a>
# **brandBrandSettingEditBrandPost**
> brandBrandSettingEditBrandPost(brandID, logginUid, BrandId, BrandName, BrandDescription, BrandLogoFileUrl, BrandLogoFile, Address, BrandPhone, Active, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **brandID** | **String**|  | [optional] [default to null] |
| **logginUid** | **String**|  | [optional] [default to null] |
| **BrandId** | **String**|  | [optional] [default to null] |
| **BrandName** | **String**|  | [optional] [default to null] |
| **BrandDescription** | **String**|  | [optional] [default to null] |
| **BrandLogoFileUrl** | **String**|  | [optional] [default to null] |
| **BrandLogoFile** | **File**|  | [optional] [default to null] |
| **Address** | **String**|  | [optional] [default to null] |
| **BrandPhone** | **String**|  | [optional] [default to null] |
| **Active** | **Boolean**|  | [optional] [default to null] |
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

<a name="brandBrandSettingGetBrandGet"></a>
# **brandBrandSettingGetBrandGet**
> brandBrandSettingGetBrandGet(email)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **email** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

