# ApiTitle.ProjectsApi

All URIs are relative to *http://localhost:9292*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getV1Projects**](ProjectsApi.md#getV1Projects) | **GET** /v1/projects | 



## getV1Projects

> getV1Projects()



List projects

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ProjectsApi();
apiInstance.getV1Projects((error, data, response) => {
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

