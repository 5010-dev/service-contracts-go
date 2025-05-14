# EventMetadata

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LoadType** | **string** |  | 
**DataQuality** | Pointer to **map[string]interface{}** |  | [optional] 
**CompletionRate** | Pointer to **float64** |  | [optional] 
**ItemCount** | Pointer to **int32** |  | [optional] 
**Timestamp** | **int64** | Unix timestamp in milliseconds | 

## Methods

### NewEventMetadata

`func NewEventMetadata(loadType string, timestamp int64, ) *EventMetadata`

NewEventMetadata instantiates a new EventMetadata object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEventMetadataWithDefaults

`func NewEventMetadataWithDefaults() *EventMetadata`

NewEventMetadataWithDefaults instantiates a new EventMetadata object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLoadType

`func (o *EventMetadata) GetLoadType() string`

GetLoadType returns the LoadType field if non-nil, zero value otherwise.

### GetLoadTypeOk

`func (o *EventMetadata) GetLoadTypeOk() (*string, bool)`

GetLoadTypeOk returns a tuple with the LoadType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadType

`func (o *EventMetadata) SetLoadType(v string)`

SetLoadType sets LoadType field to given value.


### GetDataQuality

`func (o *EventMetadata) GetDataQuality() map[string]interface{}`

GetDataQuality returns the DataQuality field if non-nil, zero value otherwise.

### GetDataQualityOk

`func (o *EventMetadata) GetDataQualityOk() (*map[string]interface{}, bool)`

GetDataQualityOk returns a tuple with the DataQuality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataQuality

`func (o *EventMetadata) SetDataQuality(v map[string]interface{})`

SetDataQuality sets DataQuality field to given value.

### HasDataQuality

`func (o *EventMetadata) HasDataQuality() bool`

HasDataQuality returns a boolean if a field has been set.

### GetCompletionRate

`func (o *EventMetadata) GetCompletionRate() float64`

GetCompletionRate returns the CompletionRate field if non-nil, zero value otherwise.

### GetCompletionRateOk

`func (o *EventMetadata) GetCompletionRateOk() (*float64, bool)`

GetCompletionRateOk returns a tuple with the CompletionRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletionRate

`func (o *EventMetadata) SetCompletionRate(v float64)`

SetCompletionRate sets CompletionRate field to given value.

### HasCompletionRate

`func (o *EventMetadata) HasCompletionRate() bool`

HasCompletionRate returns a boolean if a field has been set.

### GetItemCount

`func (o *EventMetadata) GetItemCount() int32`

GetItemCount returns the ItemCount field if non-nil, zero value otherwise.

### GetItemCountOk

`func (o *EventMetadata) GetItemCountOk() (*int32, bool)`

GetItemCountOk returns a tuple with the ItemCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemCount

`func (o *EventMetadata) SetItemCount(v int32)`

SetItemCount sets ItemCount field to given value.

### HasItemCount

`func (o *EventMetadata) HasItemCount() bool`

HasItemCount returns a boolean if a field has been set.

### GetTimestamp

`func (o *EventMetadata) GetTimestamp() int64`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *EventMetadata) GetTimestampOk() (*int64, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *EventMetadata) SetTimestamp(v int64)`

SetTimestamp sets Timestamp field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


