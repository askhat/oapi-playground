# ApiTitle.ConfigsApi

All URIs are relative to *http://localhost:9292*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getV1Configs**](ConfigsApi.md#getV1Configs) | **GET** /v1/configs | 



## getV1Configs

> getV1Configs()



List configs

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ConfigsApi();
apiInstance.getV1Configs((error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully.');
  }
});
```

### Parameters

This endpoint does not need any parameter.

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

