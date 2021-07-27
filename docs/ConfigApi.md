# ApiTitle.ConfigApi

All URIs are relative to *http://localhost:9292*

Method | HTTP request | Description
------------- | ------------- | -------------
[**deleteV1ConfigId**](ConfigApi.md#deleteV1ConfigId) | **DELETE** /v1/config/{id} | 
[**getV1ConfigId**](ConfigApi.md#getV1ConfigId) | **GET** /v1/config/{id} | 
[**postV1Config**](ConfigApi.md#postV1Config) | **POST** /v1/config | 
[**putV1ConfigId**](ConfigApi.md#putV1ConfigId) | **PUT** /v1/config/{id} | 



## deleteV1ConfigId

> deleteV1ConfigId(id)



Delete config

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ConfigApi();
let id = "id_example"; // String | 
apiInstance.deleteV1ConfigId(id, (error, data, response) => {
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
 **id** | **String**|  | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## getV1ConfigId

> getV1ConfigId(id)



Fetch config

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ConfigApi();
let id = "id_example"; // String | 
apiInstance.getV1ConfigId(id, (error, data, response) => {
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
 **id** | **String**|  | 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## postV1Config

> postV1Config(UNKNOWN_BASE_TYPE)



Create config

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ConfigApi();
let UNKNOWN_BASE_TYPE = new ApiTitle.UNKNOWN_BASE_TYPE(); // UNKNOWN_BASE_TYPE | 
apiInstance.postV1Config(UNKNOWN_BASE_TYPE, (error, data, response) => {
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


## putV1ConfigId

> putV1ConfigId(id, opts)



Update config

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ConfigApi();
let id = "id_example"; // String | 
let opts = {
  'UNKNOWN_BASE_TYPE': new ApiTitle.UNKNOWN_BASE_TYPE() // UNKNOWN_BASE_TYPE | 
};
apiInstance.putV1ConfigId(id, opts, (error, data, response) => {
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
 **id** | **String**|  | 
 **UNKNOWN_BASE_TYPE** | [**UNKNOWN_BASE_TYPE**](UNKNOWN_BASE_TYPE.md)|  | [optional] 

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

