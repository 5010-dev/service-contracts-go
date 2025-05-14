# \DefaultAPI

All URIs are relative to *http://localhost:3030*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiHealthGet**](DefaultAPI.md#ApiHealthGet) | **Get** /api/health | Health check
[**ApiTasksPost**](DefaultAPI.md#ApiTasksPost) | **Post** /api/tasks | Submit tasks (single or batch)
[**ApiWorkersHeartbeatPost**](DefaultAPI.md#ApiWorkersHeartbeatPost) | **Post** /api/workers/heartbeat | Send worker heartbeat
[**ApiWorkersRegisterPost**](DefaultAPI.md#ApiWorkersRegisterPost) | **Post** /api/workers/register | Register a worker
[**ApiWorkersTaskResultPost**](DefaultAPI.md#ApiWorkersTaskResultPost) | **Post** /api/workers/task-result | Submit task result



## ApiHealthGet

> ApiHealthGet200Response ApiHealthGet(ctx).Execute()

Health check

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.ApiHealthGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ApiHealthGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApiHealthGet`: ApiHealthGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.ApiHealthGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiApiHealthGetRequest struct via the builder pattern


### Return type

[**ApiHealthGet200Response**](ApiHealthGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiTasksPost

> ApiTasksPost(ctx).ApiTasksPostRequest(apiTasksPostRequest).Execute()

Submit tasks (single or batch)

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
	apiTasksPostRequest := openapiclient._api_tasks_post_request{ApiTasksPostRequestOneOf: openapiclient.NewApiTasksPostRequestOneOf()} // ApiTasksPostRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DefaultAPI.ApiTasksPost(context.Background()).ApiTasksPostRequest(apiTasksPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ApiTasksPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiTasksPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **apiTasksPostRequest** | [**ApiTasksPostRequest**](ApiTasksPostRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiWorkersHeartbeatPost

> ApiWorkersHeartbeatPost(ctx).WorkerStatus(workerStatus).Execute()

Send worker heartbeat

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	workerStatus := *openapiclient.NewWorkerStatus("Id_example", "Status_example", int32(123), []string{"Exchanges_example"}, time.Now()) // WorkerStatus | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DefaultAPI.ApiWorkersHeartbeatPost(context.Background()).WorkerStatus(workerStatus).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ApiWorkersHeartbeatPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiWorkersHeartbeatPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workerStatus** | [**WorkerStatus**](WorkerStatus.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiWorkersRegisterPost

> ApiWorkersRegisterPost(ctx).WorkerRegistration(workerRegistration).Execute()

Register a worker

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
	workerRegistration := *openapiclient.NewWorkerRegistration("Id_example", []openapiclient.ExchangeType{openapiclient.ExchangeType("gateio")}, int32(123), "ApiUrl_example") // WorkerRegistration | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DefaultAPI.ApiWorkersRegisterPost(context.Background()).WorkerRegistration(workerRegistration).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ApiWorkersRegisterPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiWorkersRegisterPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workerRegistration** | [**WorkerRegistration**](WorkerRegistration.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApiWorkersTaskResultPost

> ApiWorkersTaskResultPost(ctx).TaskResult(taskResult).Execute()

Submit task result

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	taskResult := *openapiclient.NewTaskResult("TaskId_example", openapiclient.ExchangeType("gateio"), openapiclient.Symbol("BTC-USDT"), openapiclient.Interval("1m"), false, time.Now()) // TaskResult | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DefaultAPI.ApiWorkersTaskResultPost(context.Background()).TaskResult(taskResult).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.ApiWorkersTaskResultPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiApiWorkersTaskResultPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **taskResult** | [**TaskResult**](TaskResult.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

