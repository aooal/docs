# UserApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**adminUserDeleteUserDelete**](UserApi.md#adminUserDeleteUserDelete) | **DELETE** /admin/User/DeleteUser |  |
| [**adminUserEditUserPost**](UserApi.md#adminUserEditUserPost) | **POST** /admin/User/EditUser |  |
| [**adminUserGetBrandsGet**](UserApi.md#adminUserGetBrandsGet) | **GET** /admin/User/GetBrands |  |
| [**adminUserGetEncryptionKeysPost**](UserApi.md#adminUserGetEncryptionKeysPost) | **POST** /admin/User/getEncryptionKeys |  |
| [**adminUserGetUserGet**](UserApi.md#adminUserGetUserGet) | **GET** /admin/User/GetUser |  |
| [**adminUserGetUserListGet**](UserApi.md#adminUserGetUserListGet) | **GET** /admin/User/GetUserList |  |
| [**adminUserRegisterPost**](UserApi.md#adminUserRegisterPost) | **POST** /admin/User/Register |  |
| [**adminUserSigninPost**](UserApi.md#adminUserSigninPost) | **POST** /admin/User/Signin |  |
| [**brandUserEditBrandUserPost**](UserApi.md#brandUserEditBrandUserPost) | **POST** /Brand/User/EditBrandUser |  |
| [**brandUserGetBrandUserGet**](UserApi.md#brandUserGetBrandUserGet) | **GET** /Brand/User/GetBrandUser |  |


<a name="adminUserDeleteUserDelete"></a>
# **adminUserDeleteUserDelete**
> adminUserDeleteUserDelete(uid)



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

<a name="adminUserEditUserPost"></a>
# **adminUserEditUserPost**
> adminUserEditUserPost(editUid, logginUid, Email, Username, Password, CheckPassword, Active, AvatarFile, AvatarFileUrl, UserID, BrandId, Area, PasswordHash, PasswordSalt, Verify, formatted\_date, BrandName, PhoneNum, Address, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **editUid** | **String**|  | [optional] [default to null] |
| **logginUid** | **String**|  | [optional] [default to null] |
| **Email** | **String**|  | [optional] [default to null] |
| **Username** | **String**|  | [optional] [default to null] |
| **Password** | **String**|  | [optional] [default to null] |
| **CheckPassword** | **String**|  | [optional] [default to null] |
| **Active** | **Boolean**|  | [optional] [default to null] |
| **AvatarFile** | **File**|  | [optional] [default to null] |
| **AvatarFileUrl** | **String**|  | [optional] [default to null] |
| **UserID** | **String**|  | [optional] [default to null] |
| **BrandId** | **String**|  | [optional] [default to null] |
| **Area** | **String**|  | [optional] [default to null] |
| **PasswordHash** | **byte[]**|  | [optional] [default to null] |
| **PasswordSalt** | **byte[]**|  | [optional] [default to null] |
| **Verify** | **Boolean**|  | [optional] [default to null] |
| **formatted\_date** | **String**|  | [optional] [default to null] |
| **BrandName** | **String**|  | [optional] [default to null] |
| **PhoneNum** | **String**|  | [optional] [default to null] |
| **Address** | **String**|  | [optional] [default to null] |
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

<a name="adminUserGetBrandsGet"></a>
# **adminUserGetBrandsGet**
> adminUserGetBrandsGet()



### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="adminUserGetEncryptionKeysPost"></a>
# **adminUserGetEncryptionKeysPost**
> adminUserGetEncryptionKeysPost()



### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="adminUserGetUserGet"></a>
# **adminUserGetUserGet**
> adminUserGetUserGet(uid)



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

<a name="adminUserGetUserListGet"></a>
# **adminUserGetUserListGet**
> adminUserGetUserListGet()



### Parameters
This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="adminUserRegisterPost"></a>
# **adminUserRegisterPost**
> adminUserRegisterPost(logginUid, Email, Username, Password, CheckPassword, Active, AvatarFile, AvatarFileUrl, UserID, BrandId, Area, PasswordHash, PasswordSalt, Verify, formatted\_date, BrandName, PhoneNum, Address, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **logginUid** | **String**|  | [optional] [default to null] |
| **Email** | **String**|  | [optional] [default to null] |
| **Username** | **String**|  | [optional] [default to null] |
| **Password** | **String**|  | [optional] [default to null] |
| **CheckPassword** | **String**|  | [optional] [default to null] |
| **Active** | **Boolean**|  | [optional] [default to null] |
| **AvatarFile** | **File**|  | [optional] [default to null] |
| **AvatarFileUrl** | **String**|  | [optional] [default to null] |
| **UserID** | **String**|  | [optional] [default to null] |
| **BrandId** | **String**|  | [optional] [default to null] |
| **Area** | **String**|  | [optional] [default to null] |
| **PasswordHash** | **byte[]**|  | [optional] [default to null] |
| **PasswordSalt** | **byte[]**|  | [optional] [default to null] |
| **Verify** | **Boolean**|  | [optional] [default to null] |
| **formatted\_date** | **String**|  | [optional] [default to null] |
| **BrandName** | **String**|  | [optional] [default to null] |
| **PhoneNum** | **String**|  | [optional] [default to null] |
| **Address** | **String**|  | [optional] [default to null] |
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

<a name="adminUserSigninPost"></a>
# **adminUserSigninPost**
> adminUserSigninPost(SignInRequest)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **SignInRequest** | [**SignInRequest**](../Models/SignInRequest.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="brandUserEditBrandUserPost"></a>
# **brandUserEditBrandUserPost**
> brandUserEditBrandUserPost(editUid, logginUid, Email, Username, Password, CheckPassword, Active, AvatarFile, AvatarFileUrl, UserID, BrandId, Area, PasswordHash, PasswordSalt, Verify, formatted\_date, BrandName, PhoneNum, Address, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **editUid** | **String**|  | [optional] [default to null] |
| **logginUid** | **String**|  | [optional] [default to null] |
| **Email** | **String**|  | [optional] [default to null] |
| **Username** | **String**|  | [optional] [default to null] |
| **Password** | **String**|  | [optional] [default to null] |
| **CheckPassword** | **String**|  | [optional] [default to null] |
| **Active** | **Boolean**|  | [optional] [default to null] |
| **AvatarFile** | **File**|  | [optional] [default to null] |
| **AvatarFileUrl** | **String**|  | [optional] [default to null] |
| **UserID** | **String**|  | [optional] [default to null] |
| **BrandId** | **String**|  | [optional] [default to null] |
| **Area** | **String**|  | [optional] [default to null] |
| **PasswordHash** | **byte[]**|  | [optional] [default to null] |
| **PasswordSalt** | **byte[]**|  | [optional] [default to null] |
| **Verify** | **Boolean**|  | [optional] [default to null] |
| **formatted\_date** | **String**|  | [optional] [default to null] |
| **BrandName** | **String**|  | [optional] [default to null] |
| **PhoneNum** | **String**|  | [optional] [default to null] |
| **Address** | **String**|  | [optional] [default to null] |
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

<a name="brandUserGetBrandUserGet"></a>
# **brandUserGetBrandUserGet**
> brandUserGetBrandUserGet(UserID)



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

