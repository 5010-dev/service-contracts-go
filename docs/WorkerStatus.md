# WorkerStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Status** | **string** |  | 
**ActiveTasks** | **int32** |  | 
**CompletedTasks** | Pointer to **int32** |  | [optional] 
**Exchanges** | **[]string** |  | 
**LastSeen** | **time.Time** |  | 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewWorkerStatus

`func NewWorkerStatus(id string, status string, activeTasks int32, exchanges []string, lastSeen time.Time, ) *WorkerStatus`

NewWorkerStatus instantiates a new WorkerStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkerStatusWithDefaults

`func NewWorkerStatusWithDefaults() *WorkerStatus`

NewWorkerStatusWithDefaults instantiates a new WorkerStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WorkerStatus) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkerStatus) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkerStatus) SetId(v string)`

SetId sets Id field to given value.


### GetStatus

`func (o *WorkerStatus) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WorkerStatus) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WorkerStatus) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetActiveTasks

`func (o *WorkerStatus) GetActiveTasks() int32`

GetActiveTasks returns the ActiveTasks field if non-nil, zero value otherwise.

### GetActiveTasksOk

`func (o *WorkerStatus) GetActiveTasksOk() (*int32, bool)`

GetActiveTasksOk returns a tuple with the ActiveTasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveTasks

`func (o *WorkerStatus) SetActiveTasks(v int32)`

SetActiveTasks sets ActiveTasks field to given value.


### GetCompletedTasks

`func (o *WorkerStatus) GetCompletedTasks() int32`

GetCompletedTasks returns the CompletedTasks field if non-nil, zero value otherwise.

### GetCompletedTasksOk

`func (o *WorkerStatus) GetCompletedTasksOk() (*int32, bool)`

GetCompletedTasksOk returns a tuple with the CompletedTasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedTasks

`func (o *WorkerStatus) SetCompletedTasks(v int32)`

SetCompletedTasks sets CompletedTasks field to given value.

### HasCompletedTasks

`func (o *WorkerStatus) HasCompletedTasks() bool`

HasCompletedTasks returns a boolean if a field has been set.

### GetExchanges

`func (o *WorkerStatus) GetExchanges() []string`

GetExchanges returns the Exchanges field if non-nil, zero value otherwise.

### GetExchangesOk

`func (o *WorkerStatus) GetExchangesOk() (*[]string, bool)`

GetExchangesOk returns a tuple with the Exchanges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchanges

`func (o *WorkerStatus) SetExchanges(v []string)`

SetExchanges sets Exchanges field to given value.


### GetLastSeen

`func (o *WorkerStatus) GetLastSeen() time.Time`

GetLastSeen returns the LastSeen field if non-nil, zero value otherwise.

### GetLastSeenOk

`func (o *WorkerStatus) GetLastSeenOk() (*time.Time, bool)`

GetLastSeenOk returns a tuple with the LastSeen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSeen

`func (o *WorkerStatus) SetLastSeen(v time.Time)`

SetLastSeen sets LastSeen field to given value.


### GetMetadata

`func (o *WorkerStatus) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *WorkerStatus) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *WorkerStatus) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *WorkerStatus) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *WorkerStatus) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *WorkerStatus) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


