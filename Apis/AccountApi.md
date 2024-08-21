# AccountApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**brandAccountChangePasswordGet**](AccountApi.md#brandAccountChangePasswordGet) | **GET** /brand/Account/change-password |  |
| [**brandAccountFeeRemainingGet**](AccountApi.md#brandAccountFeeRemainingGet) | **GET** /brand/Account/FeeRemaining |  |
| [**brandAccountLineMemberRegisterPost**](AccountApi.md#brandAccountLineMemberRegisterPost) | **POST** /brand/Account/LineMemberRegister |  |
| [**brandAccountMemberRegisterPost**](AccountApi.md#brandAccountMemberRegisterPost) | **POST** /brand/Account/MemberRegister |  |
| [**brandAccountResendVerificationEmailPost**](AccountApi.md#brandAccountResendVerificationEmailPost) | **POST** /brand/Account/ResendVerificationEmail |  |
| [**brandAccountSendChangePasswordPost**](AccountApi.md#brandAccountSendChangePasswordPost) | **POST** /brand/Account/SendChangePassword |  |
| [**brandAccountVerifyEmailGet**](AccountApi.md#brandAccountVerifyEmailGet) | **GET** /brand/Account/verify-email |  |


<a name="brandAccountChangePasswordGet"></a>
# **brandAccountChangePasswordGet**
> brandAccountChangePasswordGet(token)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **token** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

<a name="brandAccountFeeRemainingGet"></a>
# **brandAccountFeeRemainingGet**
> brandAccountFeeRemainingGet(email)



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

<a name="brandAccountLineMemberRegisterPost"></a>
# **brandAccountLineMemberRegisterPost**
> brandAccountLineMemberRegisterPost(AccountEditModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **AccountEditModel** | [**AccountEditModel**](../Models/AccountEditModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="brandAccountMemberRegisterPost"></a>
# **brandAccountMemberRegisterPost**
> brandAccountMemberRegisterPost(AccountEditModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **AccountEditModel** | [**AccountEditModel**](../Models/AccountEditModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="brandAccountResendVerificationEmailPost"></a>
# **brandAccountResendVerificationEmailPost**
> brandAccountResendVerificationEmailPost(ResendEmailModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **ResendEmailModel** | [**ResendEmailModel**](../Models/ResendEmailModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="brandAccountSendChangePasswordPost"></a>
# **brandAccountSendChangePasswordPost**
> brandAccountSendChangePasswordPost(ResendEmailModel)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **ResendEmailModel** | [**ResendEmailModel**](../Models/ResendEmailModel.md)|  | [optional] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: Not defined

<a name="brandAccountVerifyEmailGet"></a>
# **brandAccountVerifyEmailGet**
> brandAccountVerifyEmailGet(token)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **token** | **String**|  | [optional] [default to null] |

### Return type

null (empty response body)

### Authorization

[Bearer](../README.md#Bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

