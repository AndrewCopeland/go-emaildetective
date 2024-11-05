# \EmailInfoAPI

All URIs are relative to *https://api.emaildetective.io*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetBulkEmailAddressInfo**](EmailInfoAPI.md#GetBulkEmailAddressInfo) | **Post** /emails | Get information and legitimacy score for many email address
[**GetEmailAddressInfo**](EmailInfoAPI.md#GetEmailAddressInfo) | **Get** /emails/{emailAddress} | Get information and legitimacy score for an email address
[**GetEmailCSV**](EmailInfoAPI.md#GetEmailCSV) | **Post** /emails/csv | Get information and legitimacy score for many email addresses and return via CSV



## GetBulkEmailAddressInfo

> BulkEmailInfoResponse GetBulkEmailAddressInfo(ctx).BulkEmailInfoRequest(bulkEmailInfoRequest).Execute()

Get information and legitimacy score for many email address



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	bulkEmailInfoRequest := *openapiclient.NewBulkEmailInfoRequest([]string{"Data_example"}) // BulkEmailInfoRequest | Request of the email addresses to get info about

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EmailInfoAPI.GetBulkEmailAddressInfo(context.Background()).BulkEmailInfoRequest(bulkEmailInfoRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmailInfoAPI.GetBulkEmailAddressInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBulkEmailAddressInfo`: BulkEmailInfoResponse
	fmt.Fprintf(os.Stdout, "Response from `EmailInfoAPI.GetBulkEmailAddressInfo`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetBulkEmailAddressInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkEmailInfoRequest** | [**BulkEmailInfoRequest**](BulkEmailInfoRequest.md) | Request of the email addresses to get info about | 

### Return type

[**BulkEmailInfoResponse**](BulkEmailInfoResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetEmailAddressInfo

> EmailInfoResponse GetEmailAddressInfo(ctx, emailAddress).Execute()

Get information and legitimacy score for an email address



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	emailAddress := "emailAddress_example" // string | email address

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EmailInfoAPI.GetEmailAddressInfo(context.Background(), emailAddress).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmailInfoAPI.GetEmailAddressInfo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEmailAddressInfo`: EmailInfoResponse
	fmt.Fprintf(os.Stdout, "Response from `EmailInfoAPI.GetEmailAddressInfo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**emailAddress** | **string** | email address | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetEmailAddressInfoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EmailInfoResponse**](EmailInfoResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetEmailCSV

> string GetEmailCSV(ctx).Body(body).Execute()

Get information and legitimacy score for many email addresses and return via CSV



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	body := "body_example" // string | Request of the email addresses to get info about

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EmailInfoAPI.GetEmailCSV(context.Background()).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmailInfoAPI.GetEmailCSV``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEmailCSV`: string
	fmt.Fprintf(os.Stdout, "Response from `EmailInfoAPI.GetEmailCSV`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetEmailCSVRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | **string** | Request of the email addresses to get info about | 

### Return type

**string**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

- **Content-Type**: application/octet-stream
- **Accept**: text/csv, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

