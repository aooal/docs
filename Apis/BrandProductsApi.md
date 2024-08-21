# BrandProductsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**brandBrandProductsAddBrandProductPost**](BrandProductsApi.md#brandBrandProductsAddBrandProductPost) | **POST** /brand/BrandProducts/AddBrandProduct |  |
| [**brandBrandProductsDeleteBrandProductDelete**](BrandProductsApi.md#brandBrandProductsDeleteBrandProductDelete) | **DELETE** /brand/BrandProducts/DeleteBrandProduct |  |
| [**brandBrandProductsDeleteBrandProductImageDelete**](BrandProductsApi.md#brandBrandProductsDeleteBrandProductImageDelete) | **DELETE** /brand/BrandProducts/DeleteBrandProductImage |  |
| [**brandBrandProductsDeleteBrandProductPermissionsGet**](BrandProductsApi.md#brandBrandProductsDeleteBrandProductPermissionsGet) | **GET** /brand/BrandProducts/DeleteBrandProduct_permissions |  |
| [**brandBrandProductsEditProductPost**](BrandProductsApi.md#brandBrandProductsEditProductPost) | **POST** /brand/BrandProducts/EditProduct |  |
| [**brandBrandProductsGetBrandProductListGet**](BrandProductsApi.md#brandBrandProductsGetBrandProductListGet) | **GET** /brand/BrandProducts/GetBrandProductList |  |
| [**brandBrandProductsGetCategoriesDropDownGet**](BrandProductsApi.md#brandBrandProductsGetCategoriesDropDownGet) | **GET** /brand/BrandProducts/GetCategoriesDropDown |  |
| [**brandBrandProductsGetProductGet**](BrandProductsApi.md#brandBrandProductsGetProductGet) | **GET** /brand/BrandProducts/GetProduct |  |
| [**brandBrandProductsGetProductImagesGet**](BrandProductsApi.md#brandBrandProductsGetProductImagesGet) | **GET** /brand/BrandProducts/GetProductImages |  |
| [**brandBrandProductsGetStoreProductStateGet**](BrandProductsApi.md#brandBrandProductsGetStoreProductStateGet) | **GET** /brand/BrandProducts/GetStoreProductState |  |


<a name="brandBrandProductsAddBrandProductPost"></a>
# **brandBrandProductsAddBrandProductPost**
> brandBrandProductsAddBrandProductPost(logginUid, ProductId, ProductName, Price, Description, Active, ProductStatus, BrandId, Stock, ImageUrl, formatted\_date, CategoryName, FileType, CategoryId, ProductImages, DefaultImageUrls, Result, StoreProductId, StoreName, ProductStatusTranslate, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **logginUid** | **String**|  | [optional] [default to null] |
| **ProductId** | **String**|  | [optional] [default to null] |
| **ProductName** | **String**|  | [optional] [default to null] |
| **Price** | **Double**|  | [optional] [default to null] |
| **Description** | **String**|  | [optional] [default to null] |
| **Active** | **Boolean**|  | [optional] [default to null] |
| **ProductStatus** | **Boolean**|  | [optional] [default to null] |
| **BrandId** | **String**|  | [optional] [default to null] |
| **Stock** | **Integer**|  | [optional] [default to null] |
| **ImageUrl** | **String**|  | [optional] [default to null] |
| **formatted\_date** | **String**|  | [optional] [default to null] |
| **CategoryName** | **String**|  | [optional] [default to null] |
| **FileType** | **String**|  | [optional] [default to null] |
| **CategoryId** | **String**|  | [optional] [default to null] |
| **ProductImages** | **List**|  | [optional] [default to null] |
| **DefaultImageUrls** | [**List**](../Models/String.md)|  | [optional] [default to null] |
| **Result** | **Boolean**|  | [optional] [default to null] |
| **StoreProductId** | **String**|  | [optional] [default to null] |
| **StoreName** | **String**|  | [optional] [default to null] |
| **ProductStatusTranslate** | **String**|  | [optional] [default to null] |
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

<a name="brandBrandProductsDeleteBrandProductDelete"></a>
# **brandBrandProductsDeleteBrandProductDelete**
> brandBrandProductsDeleteBrandProductDelete(productId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **productId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="brandBrandProductsDeleteBrandProductImageDelete"></a>
# **brandBrandProductsDeleteBrandProductImageDelete**
> brandBrandProductsDeleteBrandProductImageDelete(url)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **url** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="brandBrandProductsDeleteBrandProductPermissionsGet"></a>
# **brandBrandProductsDeleteBrandProductPermissionsGet**
> brandBrandProductsDeleteBrandProductPermissionsGet(BrandProductID)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **BrandProductID** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="brandBrandProductsEditProductPost"></a>
# **brandBrandProductsEditProductPost**
> brandBrandProductsEditProductPost(editPid, logginUid, ProductId, ProductName, Price, Description, Active, ProductStatus, BrandId, Stock, ImageUrl, formatted\_date, CategoryName, FileType, CategoryId, ProductImages, DefaultImageUrls, Result, StoreProductId, StoreName, ProductStatusTranslate, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **editPid** | **String**|  | [optional] [default to null] |
| **logginUid** | **String**|  | [optional] [default to null] |
| **ProductId** | **String**|  | [optional] [default to null] |
| **ProductName** | **String**|  | [optional] [default to null] |
| **Price** | **Double**|  | [optional] [default to null] |
| **Description** | **String**|  | [optional] [default to null] |
| **Active** | **Boolean**|  | [optional] [default to null] |
| **ProductStatus** | **Boolean**|  | [optional] [default to null] |
| **BrandId** | **String**|  | [optional] [default to null] |
| **Stock** | **Integer**|  | [optional] [default to null] |
| **ImageUrl** | **String**|  | [optional] [default to null] |
| **formatted\_date** | **String**|  | [optional] [default to null] |
| **CategoryName** | **String**|  | [optional] [default to null] |
| **FileType** | **String**|  | [optional] [default to null] |
| **CategoryId** | **String**|  | [optional] [default to null] |
| **ProductImages** | **List**|  | [optional] [default to null] |
| **DefaultImageUrls** | [**List**](../Models/String.md)|  | [optional] [default to null] |
| **Result** | **Boolean**|  | [optional] [default to null] |
| **StoreProductId** | **String**|  | [optional] [default to null] |
| **StoreName** | **String**|  | [optional] [default to null] |
| **ProductStatusTranslate** | **String**|  | [optional] [default to null] |
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

<a name="brandBrandProductsGetBrandProductListGet"></a>
# **brandBrandProductsGetBrandProductListGet**
> brandBrandProductsGetBrandProductListGet(brandId)



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

<a name="brandBrandProductsGetCategoriesDropDownGet"></a>
# **brandBrandProductsGetCategoriesDropDownGet**
> brandBrandProductsGetCategoriesDropDownGet(brandId)



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

<a name="brandBrandProductsGetProductGet"></a>
# **brandBrandProductsGetProductGet**
> brandBrandProductsGetProductGet(productId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **productId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="brandBrandProductsGetProductImagesGet"></a>
# **brandBrandProductsGetProductImagesGet**
> brandBrandProductsGetProductImagesGet(productId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **productId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="brandBrandProductsGetStoreProductStateGet"></a>
# **brandBrandProductsGetStoreProductStateGet**
> brandBrandProductsGetStoreProductStateGet(BrandProductId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **BrandProductId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

