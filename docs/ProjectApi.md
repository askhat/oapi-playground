# ApiTitle.ProjectApi

All URIs are relative to *http://localhost:9292*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteV1ProjectId**](ProjectApi.md#deleteV1ProjectId) | **DELETE** /v1/project/{id} | 
[**getV1ProjectId**](ProjectApi.md#getV1ProjectId) | **GET** /v1/project/{id} | 
[**postV1Project**](ProjectApi.md#postV1Project) | **POST** /v1/project | 
[**putV1ProjectId**](ProjectApi.md#putV1ProjectId) | **PUT** /v1/project/{id} | 



## deleteV1ProjectId

> deleteV1ProjectId(id)



Delete project

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ProjectApi();
let id = 56; // Number | 
apiInstance.deleteV1ProjectId(id, (error, data, response) => {
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


## getV1ProjectId

> getV1ProjectId(id)



Fetch project

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ProjectApi();
let id = 56; // Number | 
apiInstance.getV1ProjectId(id, (error, data, response) => {
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


## postV1Project

> postV1Project(UNKNOWN_BASE_TYPE)



Create project

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ProjectApi();
let UNKNOWN_BASE_TYPE = new ApiTitle.UNKNOWN_BASE_TYPE(); // UNKNOWN_BASE_TYPE | 
apiInstance.postV1Project(UNKNOWN_BASE_TYPE, (error, data, response) => {
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


## putV1ProjectId

> putV1ProjectId(id, opts)



Update project

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ProjectApi();
let id = "id_example"; // String | Project identifier
let opts = {
  'UNKNOWN_BASE_TYPE': new ApiTitle.UNKNOWN_BASE_TYPE() // UNKNOWN_BASE_TYPE | 
};
apiInstance.putV1ProjectId(id, opts, (error, data, response) => {
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
 **id** | **String**| Project identifier | 
 **UNKNOWN_BASE_TYPE** | [**UNKNOWN_BASE_TYPE**](UNKNOWN_BASE_TYPE.md)|  | [optional] 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

