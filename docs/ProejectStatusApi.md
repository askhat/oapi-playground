# ApiTitle.ProejectStatusApi

All URIs are relative to *http://localhost:9292*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteV1ProejectStatusIdProejectStatus**](ProejectStatusApi.md#deleteV1ProejectStatusIdProejectStatus) | **DELETE** /v1/proeject_status/{id}/proeject_status | 
[**getV1ProejectStatusId**](ProejectStatusApi.md#getV1ProejectStatusId) | **GET** /v1/proeject_status/{id} | 
[**postV1ProejectStatus**](ProejectStatusApi.md#postV1ProejectStatus) | **POST** /v1/proeject_status | 
[**postV1ProejectStatusId**](ProejectStatusApi.md#postV1ProejectStatusId) | **POST** /v1/proeject_status/{id} | 



## deleteV1ProejectStatusIdProejectStatus

> deleteV1ProejectStatusIdProejectStatus(id)



Delete project status

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ProejectStatusApi();
let id = 56; // Number | 
apiInstance.deleteV1ProejectStatusIdProejectStatus(id, (error, data, response) => {
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


## getV1ProejectStatusId

> getV1ProejectStatusId(id)



Fetch project status

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ProejectStatusApi();
let id = 56; // Number | 
apiInstance.getV1ProejectStatusId(id, (error, data, response) => {
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


## postV1ProejectStatus

> postV1ProejectStatus(UNKNOWN_BASE_TYPE)



Create project status

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ProejectStatusApi();
let UNKNOWN_BASE_TYPE = new ApiTitle.UNKNOWN_BASE_TYPE(); // UNKNOWN_BASE_TYPE | 
apiInstance.postV1ProejectStatus(UNKNOWN_BASE_TYPE, (error, data, response) => {
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


## postV1ProejectStatusId

> postV1ProejectStatusId(id, UNKNOWN_BASE_TYPE)



Update project status

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ProejectStatusApi();
let id = 56; // Number | 
let UNKNOWN_BASE_TYPE = new ApiTitle.UNKNOWN_BASE_TYPE(); // UNKNOWN_BASE_TYPE | 
apiInstance.postV1ProejectStatusId(id, UNKNOWN_BASE_TYPE, (error, data, response) => {
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
 **UNKNOWN_BASE_TYPE** | [**UNKNOWN_BASE_TYPE**](UNKNOWN_BASE_TYPE.md)|  | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

