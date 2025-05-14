# ApiTasksPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique task identifier | 
**ExchangeType** | [**ExchangeType**](ExchangeType.md) |  | 
**Symbol** | [**Symbol**](Symbol.md) |  | 
**Interval** | [**Interval**](Interval.md) |  | 
**TaskType** | **string** |  | 
**Priority** | Pointer to **int32** | Task priority (higher &#x3D; more important) | [optional] [default to 1]
**Limit** | Pointer to **int32** | Data limit for collection | [optional] 
**StartTime** | Pointer to **NullableTime** | Start time for historical/gap tasks | [optional] 
**EndTime** | Pointer to **NullableTime** | End time for historical/gap tasks | [optional] 
**CreatedAt** | **time.Time** |  | 
**LoadContext** | Pointer to [**LoadContext**](LoadContext.md) |  | [optional] 
**Tasks** | Pointer to [**[]Task**](Task.md) |  | [optional] 

## Methods

### NewApiTasksPostRequest

`func NewApiTasksPostRequest(id string, exchangeType ExchangeType, symbol Symbol, interval Interval, taskType string, createdAt time.Time, ) *ApiTasksPostRequest`

NewApiTasksPostRequest instantiates a new ApiTasksPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiTasksPostRequestWithDefaults

`func NewApiTasksPostRequestWithDefaults() *ApiTasksPostRequest`

NewApiTasksPostRequestWithDefaults instantiates a new ApiTasksPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ApiTasksPostRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ApiTasksPostRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ApiTasksPostRequest) SetId(v string)`

SetId sets Id field to given value.


### GetExchangeType

`func (o *ApiTasksPostRequest) GetExchangeType() ExchangeType`

GetExchangeType returns the ExchangeType field if non-nil, zero value otherwise.

### GetExchangeTypeOk

`func (o *ApiTasksPostRequest) GetExchangeTypeOk() (*ExchangeType, bool)`

GetExchangeTypeOk returns a tuple with the ExchangeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeType

`func (o *ApiTasksPostRequest) SetExchangeType(v ExchangeType)`

SetExchangeType sets ExchangeType field to given value.


### GetSymbol

`func (o *ApiTasksPostRequest) GetSymbol() Symbol`

GetSymbol returns the Symbol field if non-nil, zero value otherwise.

### GetSymbolOk

`func (o *ApiTasksPostRequest) GetSymbolOk() (*Symbol, bool)`

GetSymbolOk returns a tuple with the Symbol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSymbol

`func (o *ApiTasksPostRequest) SetSymbol(v Symbol)`

SetSymbol sets Symbol field to given value.


### GetInterval

`func (o *ApiTasksPostRequest) GetInterval() Interval`

GetInterval returns the Interval field if non-nil, zero value otherwise.

### GetIntervalOk

`func (o *ApiTasksPostRequest) GetIntervalOk() (*Interval, bool)`

GetIntervalOk returns a tuple with the Interval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterval

`func (o *ApiTasksPostRequest) SetInterval(v Interval)`

SetInterval sets Interval field to given value.


### GetTaskType

`func (o *ApiTasksPostRequest) GetTaskType() string`

GetTaskType returns the TaskType field if non-nil, zero value otherwise.

### GetTaskTypeOk

`func (o *ApiTasksPostRequest) GetTaskTypeOk() (*string, bool)`

GetTaskTypeOk returns a tuple with the TaskType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskType

`func (o *ApiTasksPostRequest) SetTaskType(v string)`

SetTaskType sets TaskType field to given value.


### GetPriority

`func (o *ApiTasksPostRequest) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *ApiTasksPostRequest) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *ApiTasksPostRequest) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *ApiTasksPostRequest) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetLimit

`func (o *ApiTasksPostRequest) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ApiTasksPostRequest) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ApiTasksPostRequest) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *ApiTasksPostRequest) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetStartTime

`func (o *ApiTasksPostRequest) GetStartTime() time.Time`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *ApiTasksPostRequest) GetStartTimeOk() (*time.Time, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *ApiTasksPostRequest) SetStartTime(v time.Time)`

SetStartTime sets StartTime field to given value.

### HasStartTime

`func (o *ApiTasksPostRequest) HasStartTime() bool`

HasStartTime returns a boolean if a field has been set.

### SetStartTimeNil

`func (o *ApiTasksPostRequest) SetStartTimeNil(b bool)`

 SetStartTimeNil sets the value for StartTime to be an explicit nil

### UnsetStartTime
`func (o *ApiTasksPostRequest) UnsetStartTime()`

UnsetStartTime ensures that no value is present for StartTime, not even an explicit nil
### GetEndTime

`func (o *ApiTasksPostRequest) GetEndTime() time.Time`

GetEndTime returns the EndTime field if non-nil, zero value otherwise.

### GetEndTimeOk

`func (o *ApiTasksPostRequest) GetEndTimeOk() (*time.Time, bool)`

GetEndTimeOk returns a tuple with the EndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTime

`func (o *ApiTasksPostRequest) SetEndTime(v time.Time)`

SetEndTime sets EndTime field to given value.

### HasEndTime

`func (o *ApiTasksPostRequest) HasEndTime() bool`

HasEndTime returns a boolean if a field has been set.

### SetEndTimeNil

`func (o *ApiTasksPostRequest) SetEndTimeNil(b bool)`

 SetEndTimeNil sets the value for EndTime to be an explicit nil

### UnsetEndTime
`func (o *ApiTasksPostRequest) UnsetEndTime()`

UnsetEndTime ensures that no value is present for EndTime, not even an explicit nil
### GetCreatedAt

`func (o *ApiTasksPostRequest) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ApiTasksPostRequest) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ApiTasksPostRequest) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetLoadContext

`func (o *ApiTasksPostRequest) GetLoadContext() LoadContext`

GetLoadContext returns the LoadContext field if non-nil, zero value otherwise.

### GetLoadContextOk

`func (o *ApiTasksPostRequest) GetLoadContextOk() (*LoadContext, bool)`

GetLoadContextOk returns a tuple with the LoadContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadContext

`func (o *ApiTasksPostRequest) SetLoadContext(v LoadContext)`

SetLoadContext sets LoadContext field to given value.

### HasLoadContext

`func (o *ApiTasksPostRequest) HasLoadContext() bool`

HasLoadContext returns a boolean if a field has been set.

### GetTasks

`func (o *ApiTasksPostRequest) GetTasks() []Task`

GetTasks returns the Tasks field if non-nil, zero value otherwise.

### GetTasksOk

`func (o *ApiTasksPostRequest) GetTasksOk() (*[]Task, bool)`

GetTasksOk returns a tuple with the Tasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTasks

`func (o *ApiTasksPostRequest) SetTasks(v []Task)`

SetTasks sets Tasks field to given value.

### HasTasks

`func (o *ApiTasksPostRequest) HasTasks() bool`

HasTasks returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


