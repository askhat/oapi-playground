# ApiTitle.MonthApi

All URIs are relative to *http://localhost:9292*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteV1MonthId**](MonthApi.md#deleteV1MonthId) | **DELETE** /v1/month/{id} | 
[**getV1MonthId**](MonthApi.md#getV1MonthId) | **GET** /v1/month/{id} | 
[**postV1Month**](MonthApi.md#postV1Month) | **POST** /v1/month | 
[**putV1MonthId**](MonthApi.md#putV1MonthId) | **PUT** /v1/month/{id} | 



## deleteV1MonthId

> deleteV1MonthId(id)



Delete month

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.MonthApi();
let id = 56; // Number | 
apiInstance.deleteV1MonthId(id, (error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Number**|  | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## getV1MonthId

> getV1MonthId(id)



Fetch month

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.MonthApi();
let id = 56; // Number | 
apiInstance.getV1MonthId(id, (error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **Number**|  | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## postV1Month

> postV1Month(UNKNOWN_BASE_TYPE)



Create month

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.MonthApi();
let UNKNOWN_BASE_TYPE = new ApiTitle.UNKNOWN_BASE_TYPE(); // UNKNOWN_BASE_TYPE | 
apiInstance.postV1Month(UNKNOWN_BASE_TYPE, (error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **UNKNOWN_BASE_TYPE** | [**UNKNOWN_BASE_TYPE**](UNKNOWN_BASE_TYPE.md)|  | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## putV1MonthId

> putV1MonthId(id, opts)



Update month

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.MonthApi();
let id = "id_example"; // String | Month identifier
let opts = {
  'UNKNOWN_BASE_TYPE': new ApiTitle.UNKNOWN_BASE_TYPE() // UNKNOWN_BASE_TYPE | 
};
apiInstance.putV1MonthId(id, opts, (error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Month identifier | 
 **UNKNOWN_BASE_TYPE** | [**UNKNOWN_BASE_TYPE**](UNKNOWN_BASE_TYPE.md)|  | [optional] 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

