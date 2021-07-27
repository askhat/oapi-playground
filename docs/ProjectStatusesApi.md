# ApiTitle.ProjectStatusesApi

All URIs are relative to *http://localhost:9292*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getV1ProjectStatuses**](ProjectStatusesApi.md#getV1ProjectStatuses) | **GET** /v1/project_statuses | 



## getV1ProjectStatuses

> getV1ProjectStatuses()



List project statuses

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.ProjectStatusesApi();
apiInstance.getV1ProjectStatuses((error, data, response) => {
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

