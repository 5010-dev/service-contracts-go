# DataUpdateEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Event** | **string** |  | 
**Context** | [**DataUpdateEventContext**](DataUpdateEventContext.md) |  | 
**Metadata** | [**EventMetadata**](EventMetadata.md) |  | 
**Timestamp** | **int64** |  | 

## Methods

### NewDataUpdateEvent

`func NewDataUpdateEvent(event string, context DataUpdateEventContext, metadata EventMetadata, timestamp int64, ) *DataUpdateEvent`

NewDataUpdateEvent instantiates a new DataUpdateEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDataUpdateEventWithDefaults

`func NewDataUpdateEventWithDefaults() *DataUpdateEvent`

NewDataUpdateEventWithDefaults instantiates a new DataUpdateEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEvent

`func (o *DataUpdateEvent) GetEvent() string`

GetEvent returns the Event field if non-nil, zero value otherwise.

### GetEventOk

`func (o *DataUpdateEvent) GetEventOk() (*string, bool)`

GetEventOk returns a tuple with the Event field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvent

`func (o *DataUpdateEvent) SetEvent(v string)`

SetEvent sets Event field to given value.


### GetContext

`func (o *DataUpdateEvent) GetContext() DataUpdateEventContext`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *DataUpdateEvent) GetContextOk() (*DataUpdateEventContext, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *DataUpdateEvent) SetContext(v DataUpdateEventContext)`

SetContext sets Context field to given value.


### GetMetadata

`func (o *DataUpdateEvent) GetMetadata() EventMetadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DataUpdateEvent) GetMetadataOk() (*EventMetadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DataUpdateEvent) SetMetadata(v EventMetadata)`

SetMetadata sets Metadata field to given value.


### GetTimestamp

`func (o *DataUpdateEvent) GetTimestamp() int64`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *DataUpdateEvent) GetTimestampOk() (*int64, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *DataUpdateEvent) SetTimestamp(v int64)`

SetTimestamp sets Timestamp field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


