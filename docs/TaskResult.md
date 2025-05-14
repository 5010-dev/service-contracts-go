# TaskResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TaskId** | **string** |  | 
**ParentId** | Pointer to **NullableString** |  | [optional] 
**ExchangeType** | [**ExchangeType**](ExchangeType.md) |  | 
**Symbol** | [**Symbol**](Symbol.md) |  | 
**Interval** | [**Interval**](Interval.md) |  | 
**TaskType** | Pointer to **NullableString** |  | [optional] 
**Completed** | **bool** |  | 
**Error** | Pointer to **NullableString** |  | [optional] 
**Data** | Pointer to **map[string]interface{}** |  | [optional] 
**ItemCount** | Pointer to **NullableInt32** |  | [optional] 
**WorkerId** | Pointer to **NullableString** |  | [optional] 
**ProcessedAt** | **time.Time** |  | 

## Methods

### NewTaskResult

`func NewTaskResult(taskId string, exchangeType ExchangeType, symbol Symbol, interval Interval, completed bool, processedAt time.Time, ) *TaskResult`

NewTaskResult instantiates a new TaskResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskResultWithDefaults

`func NewTaskResultWithDefaults() *TaskResult`

NewTaskResultWithDefaults instantiates a new TaskResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTaskId

`func (o *TaskResult) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *TaskResult) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *TaskResult) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### GetParentId

`func (o *TaskResult) GetParentId() string`

GetParentId returns the ParentId field if non-nil, zero value otherwise.

### GetParentIdOk

`func (o *TaskResult) GetParentIdOk() (*string, bool)`

GetParentIdOk returns a tuple with the ParentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentId

`func (o *TaskResult) SetParentId(v string)`

SetParentId sets ParentId field to given value.

### HasParentId

`func (o *TaskResult) HasParentId() bool`

HasParentId returns a boolean if a field has been set.

### SetParentIdNil

`func (o *TaskResult) SetParentIdNil(b bool)`

 SetParentIdNil sets the value for ParentId to be an explicit nil

### UnsetParentId
`func (o *TaskResult) UnsetParentId()`

UnsetParentId ensures that no value is present for ParentId, not even an explicit nil
### GetExchangeType

`func (o *TaskResult) GetExchangeType() ExchangeType`

GetExchangeType returns the ExchangeType field if non-nil, zero value otherwise.

### GetExchangeTypeOk

`func (o *TaskResult) GetExchangeTypeOk() (*ExchangeType, bool)`

GetExchangeTypeOk returns a tuple with the ExchangeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeType

`func (o *TaskResult) SetExchangeType(v ExchangeType)`

SetExchangeType sets ExchangeType field to given value.


### GetSymbol

`func (o *TaskResult) GetSymbol() Symbol`

GetSymbol returns the Symbol field if non-nil, zero value otherwise.

### GetSymbolOk

`func (o *TaskResult) GetSymbolOk() (*Symbol, bool)`

GetSymbolOk returns a tuple with the Symbol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSymbol

`func (o *TaskResult) SetSymbol(v Symbol)`

SetSymbol sets Symbol field to given value.


### GetInterval

`func (o *TaskResult) GetInterval() Interval`

GetInterval returns the Interval field if non-nil, zero value otherwise.

### GetIntervalOk

`func (o *TaskResult) GetIntervalOk() (*Interval, bool)`

GetIntervalOk returns a tuple with the Interval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterval

`func (o *TaskResult) SetInterval(v Interval)`

SetInterval sets Interval field to given value.


### GetTaskType

`func (o *TaskResult) GetTaskType() string`

GetTaskType returns the TaskType field if non-nil, zero value otherwise.

### GetTaskTypeOk

`func (o *TaskResult) GetTaskTypeOk() (*string, bool)`

GetTaskTypeOk returns a tuple with the TaskType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskType

`func (o *TaskResult) SetTaskType(v string)`

SetTaskType sets TaskType field to given value.

### HasTaskType

`func (o *TaskResult) HasTaskType() bool`

HasTaskType returns a boolean if a field has been set.

### SetTaskTypeNil

`func (o *TaskResult) SetTaskTypeNil(b bool)`

 SetTaskTypeNil sets the value for TaskType to be an explicit nil

### UnsetTaskType
`func (o *TaskResult) UnsetTaskType()`

UnsetTaskType ensures that no value is present for TaskType, not even an explicit nil
### GetCompleted

`func (o *TaskResult) GetCompleted() bool`

GetCompleted returns the Completed field if non-nil, zero value otherwise.

### GetCompletedOk

`func (o *TaskResult) GetCompletedOk() (*bool, bool)`

GetCompletedOk returns a tuple with the Completed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompleted

`func (o *TaskResult) SetCompleted(v bool)`

SetCompleted sets Completed field to given value.


### GetError

`func (o *TaskResult) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *TaskResult) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *TaskResult) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *TaskResult) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *TaskResult) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *TaskResult) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetData

`func (o *TaskResult) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TaskResult) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TaskResult) SetData(v map[string]interface{})`

SetData sets Data field to given value.

### HasData

`func (o *TaskResult) HasData() bool`

HasData returns a boolean if a field has been set.

### SetDataNil

`func (o *TaskResult) SetDataNil(b bool)`

 SetDataNil sets the value for Data to be an explicit nil

### UnsetData
`func (o *TaskResult) UnsetData()`

UnsetData ensures that no value is present for Data, not even an explicit nil
### GetItemCount

`func (o *TaskResult) GetItemCount() int32`

GetItemCount returns the ItemCount field if non-nil, zero value otherwise.

### GetItemCountOk

`func (o *TaskResult) GetItemCountOk() (*int32, bool)`

GetItemCountOk returns a tuple with the ItemCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemCount

`func (o *TaskResult) SetItemCount(v int32)`

SetItemCount sets ItemCount field to given value.

### HasItemCount

`func (o *TaskResult) HasItemCount() bool`

HasItemCount returns a boolean if a field has been set.

### SetItemCountNil

`func (o *TaskResult) SetItemCountNil(b bool)`

 SetItemCountNil sets the value for ItemCount to be an explicit nil

### UnsetItemCount
`func (o *TaskResult) UnsetItemCount()`

UnsetItemCount ensures that no value is present for ItemCount, not even an explicit nil
### GetWorkerId

`func (o *TaskResult) GetWorkerId() string`

GetWorkerId returns the WorkerId field if non-nil, zero value otherwise.

### GetWorkerIdOk

`func (o *TaskResult) GetWorkerIdOk() (*string, bool)`

GetWorkerIdOk returns a tuple with the WorkerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkerId

`func (o *TaskResult) SetWorkerId(v string)`

SetWorkerId sets WorkerId field to given value.

### HasWorkerId

`func (o *TaskResult) HasWorkerId() bool`

HasWorkerId returns a boolean if a field has been set.

### SetWorkerIdNil

`func (o *TaskResult) SetWorkerIdNil(b bool)`

 SetWorkerIdNil sets the value for WorkerId to be an explicit nil

### UnsetWorkerId
`func (o *TaskResult) UnsetWorkerId()`

UnsetWorkerId ensures that no value is present for WorkerId, not even an explicit nil
### GetProcessedAt

`func (o *TaskResult) GetProcessedAt() time.Time`

GetProcessedAt returns the ProcessedAt field if non-nil, zero value otherwise.

### GetProcessedAtOk

`func (o *TaskResult) GetProcessedAtOk() (*time.Time, bool)`

GetProcessedAtOk returns a tuple with the ProcessedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessedAt

`func (o *TaskResult) SetProcessedAt(v time.Time)`

SetProcessedAt sets ProcessedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


