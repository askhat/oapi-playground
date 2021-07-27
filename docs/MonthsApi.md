# ApiTitle.MonthsApi

All URIs are relative to *http://localhost:9292*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getV1Months**](MonthsApi.md#getV1Months) | **GET** /v1/months | 



## getV1Months

> getV1Months()



List months

### Example

```javascript
import ApiTitle from 'api_title';

let apiInstance = new ApiTitle.MonthsApi();
apiInstance.getV1Months((error, data, response) => {
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

