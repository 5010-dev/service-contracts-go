# Task

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

## Methods

### NewTask

`func NewTask(id string, exchangeType ExchangeType, symbol Symbol, interval Interval, taskType string, createdAt time.Time, ) *Task`

NewTask instantiates a new Task object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskWithDefaults

`func NewTaskWithDefaults() *Task`

NewTaskWithDefaults instantiates a new Task object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Task) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Task) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Task) SetId(v string)`

SetId sets Id field to given value.


### GetExchangeType

`func (o *Task) GetExchangeType() ExchangeType`

GetExchangeType returns the ExchangeType field if non-nil, zero value otherwise.

### GetExchangeTypeOk

`func (o *Task) GetExchangeTypeOk() (*ExchangeType, bool)`

GetExchangeTypeOk returns a tuple with the ExchangeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeType

`func (o *Task) SetExchangeType(v ExchangeType)`

SetExchangeType sets ExchangeType field to given value.


### GetSymbol

`func (o *Task) GetSymbol() Symbol`

GetSymbol returns the Symbol field if non-nil, zero value otherwise.

### GetSymbolOk

`func (o *Task) GetSymbolOk() (*Symbol, bool)`

GetSymbolOk returns a tuple with the Symbol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSymbol

`func (o *Task) SetSymbol(v Symbol)`

SetSymbol sets Symbol field to given value.


### GetInterval

`func (o *Task) GetInterval() Interval`

GetInterval returns the Interval field if non-nil, zero value otherwise.

### GetIntervalOk

`func (o *Task) GetIntervalOk() (*Interval, bool)`

GetIntervalOk returns a tuple with the Interval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterval

`func (o *Task) SetInterval(v Interval)`

SetInterval sets Interval field to given value.


### GetTaskType

`func (o *Task) GetTaskType() string`

GetTaskType returns the TaskType field if non-nil, zero value otherwise.

### GetTaskTypeOk

`func (o *Task) GetTaskTypeOk() (*string, bool)`

GetTaskTypeOk returns a tuple with the TaskType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskType

`func (o *Task) SetTaskType(v string)`

SetTaskType sets TaskType field to given value.


### GetPriority

`func (o *Task) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *Task) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *Task) SetPriority(v int32)`

SetPriority sets Priority field to given value.

### HasPriority

`func (o *Task) HasPriority() bool`

HasPriority returns a boolean if a field has been set.

### GetLimit

`func (o *Task) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *Task) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *Task) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *Task) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetStartTime

`func (o *Task) GetStartTime() time.Time`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *Task) GetStartTimeOk() (*time.Time, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *Task) SetStartTime(v time.Time)`

SetStartTime sets StartTime field to given value.

### HasStartTime

`func (o *Task) HasStartTime() bool`

HasStartTime returns a boolean if a field has been set.

### SetStartTimeNil

`func (o *Task) SetStartTimeNil(b bool)`

 SetStartTimeNil sets the value for StartTime to be an explicit nil

### UnsetStartTime
`func (o *Task) UnsetStartTime()`

UnsetStartTime ensures that no value is present for StartTime, not even an explicit nil
### GetEndTime

`func (o *Task) GetEndTime() time.Time`

GetEndTime returns the EndTime field if non-nil, zero value otherwise.

### GetEndTimeOk

`func (o *Task) GetEndTimeOk() (*time.Time, bool)`

GetEndTimeOk returns a tuple with the EndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTime

`func (o *Task) SetEndTime(v time.Time)`

SetEndTime sets EndTime field to given value.

### HasEndTime

`func (o *Task) HasEndTime() bool`

HasEndTime returns a boolean if a field has been set.

### SetEndTimeNil

`func (o *Task) SetEndTimeNil(b bool)`

 SetEndTimeNil sets the value for EndTime to be an explicit nil

### UnsetEndTime
`func (o *Task) UnsetEndTime()`

UnsetEndTime ensures that no value is present for EndTime, not even an explicit nil
### GetCreatedAt

`func (o *Task) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Task) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Task) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetLoadContext

`func (o *Task) GetLoadContext() LoadContext`

GetLoadContext returns the LoadContext field if non-nil, zero value otherwise.

### GetLoadContextOk

`func (o *Task) GetLoadContextOk() (*LoadContext, bool)`

GetLoadContextOk returns a tuple with the LoadContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadContext

`func (o *Task) SetLoadContext(v LoadContext)`

SetLoadContext sets LoadContext field to given value.

### HasLoadContext

`func (o *Task) HasLoadContext() bool`

HasLoadContext returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


