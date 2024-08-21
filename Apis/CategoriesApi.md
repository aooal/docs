# CategoriesApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**brandCategoriesAddCategoryPost**](CategoriesApi.md#brandCategoriesAddCategoryPost) | **POST** /brand/Categories/AddCategory |  |
| [**brandCategoriesDeleteCategoryDelete**](CategoriesApi.md#brandCategoriesDeleteCategoryDelete) | **DELETE** /brand/Categories/DeleteCategory |  |
| [**brandCategoriesEditCategoryPost**](CategoriesApi.md#brandCategoriesEditCategoryPost) | **POST** /brand/Categories/EditCategory |  |
| [**brandCategoriesGetCategoryGet**](CategoriesApi.md#brandCategoriesGetCategoryGet) | **GET** /brand/Categories/GetCategory |  |
| [**brandCategoriesGetCategoryListGet**](CategoriesApi.md#brandCategoriesGetCategoryListGet) | **GET** /brand/Categories/GetCategoryList |  |


<a name="brandCategoriesAddCategoryPost"></a>
# **brandCategoriesAddCategoryPost**
> brandCategoriesAddCategoryPost(logginUid, CategoriesEditModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **logginUid** | **String**|  | [optional] [default to null] |
| **CategoriesEditModel** | [**CategoriesEditModel**](../Models/CategoriesEditModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="brandCategoriesDeleteCategoryDelete"></a>
# **brandCategoriesDeleteCategoryDelete**
> brandCategoriesDeleteCategoryDelete(categoryId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **categoryId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="brandCategoriesEditCategoryPost"></a>
# **brandCategoriesEditCategoryPost**
> brandCategoriesEditCategoryPost(categoryId, logginUid, CategoriesEditModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **categoryId** | **String**|  | [optional] [default to null] |
| **logginUid** | **String**|  | [optional] [default to null] |
| **CategoriesEditModel** | [**CategoriesEditModel**](../Models/CategoriesEditModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="brandCategoriesGetCategoryGet"></a>
# **brandCategoriesGetCategoryGet**
> brandCategoriesGetCategoryGet(categoryId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **categoryId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="brandCategoriesGetCategoryListGet"></a>
# **brandCategoriesGetCategoryListGet**
> brandCategoriesGetCategoryListGet(brandId)



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

