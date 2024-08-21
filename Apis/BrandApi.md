# BrandApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**adminBrandAddBrandPost**](BrandApi.md#adminBrandAddBrandPost) | **POST** /admin/Brand/AddBrand |  |
| [**adminBrandDeleteBrandsDelete**](BrandApi.md#adminBrandDeleteBrandsDelete) | **DELETE** /admin/Brand/DeleteBrands |  |
| [**adminBrandEditBrandPost**](BrandApi.md#adminBrandEditBrandPost) | **POST** /admin/Brand/EditBrand |  |
| [**adminBrandGetAllBrandGet**](BrandApi.md#adminBrandGetAllBrandGet) | **GET** /admin/Brand/GetAllBrand |  |
| [**adminBrandGetBrandGet**](BrandApi.md#adminBrandGetBrandGet) | **GET** /admin/Brand/GetBrand |  |
| [**brandBrandEditBrandPost**](BrandApi.md#brandBrandEditBrandPost) | **POST** /Brand/Brand/EditBrand |  |
| [**brandBrandGetAllBrandGet**](BrandApi.md#brandBrandGetAllBrandGet) | **GET** /Brand/Brand/GetAllBrand |  |


<a name="adminBrandAddBrandPost"></a>
# **adminBrandAddBrandPost**
> adminBrandAddBrandPost(logginUid, BrandId, BrandName, BrandDescription, BrandLogoFileUrl, BrandLogoFile, Address, BrandPhone, Active, formatted\_date, PlanName, PlanId, PlanDescription, BrandSubCount, formatted\_CreatedDate, formatted\_UpdateDate, SubscriptionEndDate, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



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
| **formatted\_date** | **String**|  | [optional] [default to null] |
| **PlanName** | **String**|  | [optional] [default to null] |
| **PlanId** | **String**|  | [optional] [default to null] |
| **PlanDescription** | **String**|  | [optional] [default to null] |
| **BrandSubCount** | **String**|  | [optional] [default to null] |
| **formatted\_CreatedDate** | **String**|  | [optional] [default to null] |
| **formatted\_UpdateDate** | **String**|  | [optional] [default to null] |
| **SubscriptionEndDate** | **String**|  | [optional] [default to null] |
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

<a name="adminBrandDeleteBrandsDelete"></a>
# **adminBrandDeleteBrandsDelete**
> adminBrandDeleteBrandsDelete(brandID)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **brandID** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="adminBrandEditBrandPost"></a>
# **adminBrandEditBrandPost**
> adminBrandEditBrandPost(brandID, logginUid, BrandId, BrandName, BrandDescription, BrandLogoFileUrl, BrandLogoFile, Address, BrandPhone, Active, formatted\_date, PlanName, PlanId, PlanDescription, BrandSubCount, formatted\_CreatedDate, formatted\_UpdateDate, SubscriptionEndDate, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



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
| **formatted\_date** | **String**|  | [optional] [default to null] |
| **PlanName** | **String**|  | [optional] [default to null] |
| **PlanId** | **String**|  | [optional] [default to null] |
| **PlanDescription** | **String**|  | [optional] [default to null] |
| **BrandSubCount** | **String**|  | [optional] [default to null] |
| **formatted\_CreatedDate** | **String**|  | [optional] [default to null] |
| **formatted\_UpdateDate** | **String**|  | [optional] [default to null] |
| **SubscriptionEndDate** | **String**|  | [optional] [default to null] |
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

<a name="adminBrandGetAllBrandGet"></a>
# **adminBrandGetAllBrandGet**
> adminBrandGetAllBrandGet()



### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="adminBrandGetBrandGet"></a>
# **adminBrandGetBrandGet**
> adminBrandGetBrandGet(brandID)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **brandID** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="brandBrandEditBrandPost"></a>
# **brandBrandEditBrandPost**
> brandBrandEditBrandPost(brandID, logginUid, BrandId, BrandName, BrandDescription, BrandLogoFileUrl, BrandLogoFile, Address, BrandPhone, Active, formatted\_date, PlanName, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



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
| **formatted\_date** | **String**|  | [optional] [default to null] |
| **PlanName** | **String**|  | [optional] [default to null] |
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

<a name="brandBrandGetAllBrandGet"></a>
# **brandBrandGetAllBrandGet**
> brandBrandGetAllBrandGet(UserID)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **UserID** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

