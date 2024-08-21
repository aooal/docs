# StoreOpenScheduleApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|------------- | ------------- | -------------|
| [**storeStoreOpenScheduleAddStoreOpenSchedulePost**](StoreOpenScheduleApi.md#storeStoreOpenScheduleAddStoreOpenSchedulePost) | **POST** /store/StoreOpenSchedule/AddStoreOpenSchedule |  |
| [**storeStoreOpenScheduleGetStoreOpenScheduleGet**](StoreOpenScheduleApi.md#storeStoreOpenScheduleGetStoreOpenScheduleGet) | **GET** /store/StoreOpenSchedule/GetStoreOpenSchedule |  |
| [**storeStoreOpenScheduleUpdateStoreOpenSchedulePost**](StoreOpenScheduleApi.md#storeStoreOpenScheduleUpdateStoreOpenSchedulePost) | **POST** /store/StoreOpenSchedule/UpdateStoreOpenSchedule |  |


<a name="storeStoreOpenScheduleAddStoreOpenSchedulePost"></a>
# **storeStoreOpenScheduleAddStoreOpenSchedulePost**
> storeStoreOpenScheduleAddStoreOpenSchedulePost(logginUid, storeId, Id, OsId, Wd\_T, Sd\_T, StoreId, St\_Time, End\_Time, WeekdayOff, SpecificDayOff, ExistsWdString, ExistsSpString, ExWd\_T, ExSd\_T, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **logginUid** | **String**|  | [optional] [default to null] |
| **storeId** | **String**|  | [optional] [default to null] |
| **Id** | **String**|  | [optional] [default to null] |
| **OsId** | **String**|  | [optional] [default to null] |
| **Wd\_T** | [**List**](../Models/Store_WeeklyDayoff.md)|  | [optional] [default to null] |
| **Sd\_T** | [**List**](../Models/Store_SpecificDayoff.md)|  | [optional] [default to null] |
| **StoreId** | **String**|  | [optional] [default to null] |
| **St\_Time** | **Date**|  | [optional] [default to null] |
| **End\_Time** | **Date**|  | [optional] [default to null] |
| **WeekdayOff** | **String**|  | [optional] [default to null] |
| **SpecificDayOff** | **String**|  | [optional] [default to null] |
| **ExistsWdString** | **String**|  | [optional] [default to null] |
| **ExistsSpString** | **String**|  | [optional] [default to null] |
| **ExWd\_T** | [**List**](../Models/Store_WeeklyDayoff.md)|  | [optional] [default to null] |
| **ExSd\_T** | [**List**](../Models/Store_SpecificDayoff.md)|  | [optional] [default to null] |
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

<a name="storeStoreOpenScheduleGetStoreOpenScheduleGet"></a>
# **storeStoreOpenScheduleGetStoreOpenScheduleGet**
> storeStoreOpenScheduleGetStoreOpenScheduleGet(storeId)



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

<a name="storeStoreOpenScheduleUpdateStoreOpenSchedulePost"></a>
# **storeStoreOpenScheduleUpdateStoreOpenSchedulePost**
> storeStoreOpenScheduleUpdateStoreOpenSchedulePost(logginUid, storeId, Id, OsId, Wd\_T, Sd\_T, StoreId, St\_Time, End\_Time, WeekdayOff, SpecificDayOff, ExistsWdString, ExistsSpString, ExWd\_T, ExSd\_T, CreatedName, CreatedDate, CreatedUid, UpdateUid, UpdateDate, UpdateName)



### Parameters

|Name | Type | Description  | Notes |
|------------- | ------------- | ------------- | -------------|
| **logginUid** | **String**|  | [optional] [default to null] |
| **storeId** | **String**|  | [optional] [default to null] |
| **Id** | **String**|  | [optional] [default to null] |
| **OsId** | **String**|  | [optional] [default to null] |
| **Wd\_T** | [**List**](../Models/Store_WeeklyDayoff.md)|  | [optional] [default to null] |
| **Sd\_T** | [**List**](../Models/Store_SpecificDayoff.md)|  | [optional] [default to null] |
| **StoreId** | **String**|  | [optional] [default to null] |
| **St\_Time** | **Date**|  | [optional] [default to null] |
| **End\_Time** | **Date**|  | [optional] [default to null] |
| **WeekdayOff** | **String**|  | [optional] [default to null] |
| **SpecificDayOff** | **String**|  | [optional] [default to null] |
| **ExistsWdString** | **String**|  | [optional] [default to null] |
| **ExistsSpString** | **String**|  | [optional] [default to null] |
| **ExWd\_T** | [**List**](../Models/Store_WeeklyDayoff.md)|  | [optional] [default to null] |
| **ExSd\_T** | [**List**](../Models/Store_SpecificDayoff.md)|  | [optional] [default to null] |
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

