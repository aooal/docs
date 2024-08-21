# ProductApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**storeProductCheckStoreProductCreatePermissionGet**](ProductApi.md#storeProductCheckStoreProductCreatePermissionGet) | **GET** /StoreProduct/CheckStoreProductCreatePermission |  |
| [**storeProductDeleteProductDelete**](ProductApi.md#storeProductDeleteProductDelete) | **DELETE** /StoreProduct/DeleteProduct |  |
| [**storeProductDeleteStoreProductImageDelete**](ProductApi.md#storeProductDeleteStoreProductImageDelete) | **DELETE** /StoreProduct/DeleteStoreProductImage |  |
| [**storeProductEditproductPost**](ProductApi.md#storeProductEditproductPost) | **POST** /StoreProduct/Editproduct |  |
| [**storeProductGetCategoriesDropDownGet**](ProductApi.md#storeProductGetCategoriesDropDownGet) | **GET** /StoreProduct/GetCategoriesDropDown |  |
| [**storeProductGetProductGet**](ProductApi.md#storeProductGetProductGet) | **GET** /StoreProduct/GetProduct |  |
| [**storeProductGetProductListGet**](ProductApi.md#storeProductGetProductListGet) | **GET** /StoreProduct/GetProductList |  |
| [**storeProductGetStoreProductImagesGet**](ProductApi.md#storeProductGetStoreProductImagesGet) | **GET** /StoreProduct/GetStoreProductImages |  |
| [**storeProductIsExistsBrandProductIDGet**](ProductApi.md#storeProductIsExistsBrandProductIDGet) | **GET** /StoreProduct/IsExistsBrandProductID |  |
| [**storeProductStoreAddProductPost**](ProductApi.md#storeProductStoreAddProductPost) | **POST** /StoreProduct/StoreAddProduct |  |


<a name="storeProductCheckStoreProductCreatePermissionGet"></a>
# **storeProductCheckStoreProductCreatePermissionGet**
> Boolean storeProductCheckStoreProductCreatePermissionGet(storeId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **storeId** | **String**|  | [optional] [default to null] |

### Return type

**Boolean**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

<a name="storeProductDeleteProductDelete"></a>
# **storeProductDeleteProductDelete**
> storeProductDeleteProductDelete(productId)



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

<a name="storeProductDeleteStoreProductImageDelete"></a>
# **storeProductDeleteStoreProductImageDelete**
> storeProductDeleteStoreProductImageDelete(url)



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

<a name="storeProductEditproductPost"></a>
# **storeProductEditproductPost**
> storeProductEditproductPost(editPid, logginUid, storeId, existBrandProduct, ProductId, ProductName, Price, Description, Active, StoreId, Stock, ProductStatus, AllowProductManagement, isBrand, CategoryId, CategoryName, ProductImages, DefaultImageUrls, ImageUrl, StoreProductId, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **editPid** | **String**|  | [optional] [default to null] |
| **logginUid** | **String**|  | [optional] [default to null] |
| **storeId** | **String**|  | [optional] [default to null] |
| **existBrandProduct** | **Boolean**|  | [optional] [default to null] |
| **ProductId** | **String**|  | [optional] [default to null] |
| **ProductName** | **String**|  | [optional] [default to null] |
| **Price** | **Double**|  | [optional] [default to null] |
| **Description** | **String**|  | [optional] [default to null] |
| **Active** | **Boolean**|  | [optional] [default to null] |
| **StoreId** | **String**|  | [optional] [default to null] |
| **Stock** | **Integer**|  | [optional] [default to null] |
| **ProductStatus** | **Boolean**|  | [optional] [default to null] |
| **AllowProductManagement** | **Boolean**|  | [optional] [default to null] |
| **isBrand** | **Boolean**|  | [optional] [default to null] |
| **CategoryId** | **String**|  | [optional] [default to null] |
| **CategoryName** | **String**|  | [optional] [default to null] |
| **ProductImages** | **List**|  | [optional] [default to null] |
| **DefaultImageUrls** | [**List**](../Models/String.md)|  | [optional] [default to null] |
| **ImageUrl** | **String**|  | [optional] [default to null] |
| **StoreProductId** | **String**|  | [optional] [default to null] |
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

<a name="storeProductGetCategoriesDropDownGet"></a>
# **storeProductGetCategoriesDropDownGet**
> storeProductGetCategoriesDropDownGet(brandId)



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

<a name="storeProductGetProductGet"></a>
# **storeProductGetProductGet**
> storeProductGetProductGet(productId, storeId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **productId** | **String**|  | [optional] [default to null] |
| **storeId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="storeProductGetProductListGet"></a>
# **storeProductGetProductListGet**
> storeProductGetProductListGet(storeId, brandId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **storeId** | **String**|  | [optional] [default to null] |
| **brandId** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="storeProductGetStoreProductImagesGet"></a>
# **storeProductGetStoreProductImagesGet**
> storeProductGetStoreProductImagesGet(productId)



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

<a name="storeProductIsExistsBrandProductIDGet"></a>
# **storeProductIsExistsBrandProductIDGet**
> Boolean storeProductIsExistsBrandProductIDGet(storeProductId)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **storeProductId** | **String**|  | [optional] [default to null] |

### Return type

**Boolean**

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

<a name="storeProductStoreAddProductPost"></a>
# **storeProductStoreAddProductPost**
> storeProductStoreAddProductPost(logginUid, Storeid, existBrandProduct, ProductId, ProductName, Price, Description, Active, StoreId, Stock, ProductStatus, AllowProductManagement, isBrand, CategoryId, CategoryName, ProductImages, DefaultImageUrls, ImageUrl, StoreProductId, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **logginUid** | **String**|  | [optional] [default to null] |
| **Storeid** | **String**|  | [optional] [default to null] |
| **existBrandProduct** | **Boolean**|  | [optional] [default to null] |
| **ProductId** | **String**|  | [optional] [default to null] |
| **ProductName** | **String**|  | [optional] [default to null] |
| **Price** | **Double**|  | [optional] [default to null] |
| **Description** | **String**|  | [optional] [default to null] |
| **Active** | **Boolean**|  | [optional] [default to null] |
| **StoreId** | **String**|  | [optional] [default to null] |
| **Stock** | **Integer**|  | [optional] [default to null] |
| **ProductStatus** | **Boolean**|  | [optional] [default to null] |
| **AllowProductManagement** | **Boolean**|  | [optional] [default to null] |
| **isBrand** | **Boolean**|  | [optional] [default to null] |
| **CategoryId** | **String**|  | [optional] [default to null] |
| **CategoryName** | **String**|  | [optional] [default to null] |
| **ProductImages** | **List**|  | [optional] [default to null] |
| **DefaultImageUrls** | [**List**](../Models/String.md)|  | [optional] [default to null] |
| **ImageUrl** | **String**|  | [optional] [default to null] |
| **StoreProductId** | **String**|  | [optional] [default to null] |
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

