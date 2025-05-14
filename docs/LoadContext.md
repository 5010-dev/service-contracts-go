# LoadContext

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LoadType** | **string** |  | 
**StartTime** | **time.Time** |  | 
**BatchId** | Pointer to **NullableString** |  | [optional] 
**TargetSize** | Pointer to **NullableInt32** |  | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewLoadContext

`func NewLoadContext(loadType string, startTime time.Time, ) *LoadContext`

NewLoadContext instantiates a new LoadContext object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoadContextWithDefaults

`func NewLoadContextWithDefaults() *LoadContext`

NewLoadContextWithDefaults instantiates a new LoadContext object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLoadType

`func (o *LoadContext) GetLoadType() string`

GetLoadType returns the LoadType field if non-nil, zero value otherwise.

### GetLoadTypeOk

`func (o *LoadContext) GetLoadTypeOk() (*string, bool)`

GetLoadTypeOk returns a tuple with the LoadType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoadType

`func (o *LoadContext) SetLoadType(v string)`

SetLoadType sets LoadType field to given value.


### GetStartTime

`func (o *LoadContext) GetStartTime() time.Time`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *LoadContext) GetStartTimeOk() (*time.Time, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *LoadContext) SetStartTime(v time.Time)`

SetStartTime sets StartTime field to given value.


### GetBatchId

`func (o *LoadContext) GetBatchId() string`

GetBatchId returns the BatchId field if non-nil, zero value otherwise.

### GetBatchIdOk

`func (o *LoadContext) GetBatchIdOk() (*string, bool)`

GetBatchIdOk returns a tuple with the BatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchId

`func (o *LoadContext) SetBatchId(v string)`

SetBatchId sets BatchId field to given value.

### HasBatchId

`func (o *LoadContext) HasBatchId() bool`

HasBatchId returns a boolean if a field has been set.

### SetBatchIdNil

`func (o *LoadContext) SetBatchIdNil(b bool)`

 SetBatchIdNil sets the value for BatchId to be an explicit nil

### UnsetBatchId
`func (o *LoadContext) UnsetBatchId()`

UnsetBatchId ensures that no value is present for BatchId, not even an explicit nil
### GetTargetSize

`func (o *LoadContext) GetTargetSize() int32`

GetTargetSize returns the TargetSize field if non-nil, zero value otherwise.

### GetTargetSizeOk

`func (o *LoadContext) GetTargetSizeOk() (*int32, bool)`

GetTargetSizeOk returns a tuple with the TargetSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetSize

`func (o *LoadContext) SetTargetSize(v int32)`

SetTargetSize sets TargetSize field to given value.

### HasTargetSize

`func (o *LoadContext) HasTargetSize() bool`

HasTargetSize returns a boolean if a field has been set.

### SetTargetSizeNil

`func (o *LoadContext) SetTargetSizeNil(b bool)`

 SetTargetSizeNil sets the value for TargetSize to be an explicit nil

### UnsetTargetSize
`func (o *LoadContext) UnsetTargetSize()`

UnsetTargetSize ensures that no value is present for TargetSize, not even an explicit nil
### GetMetadata

`func (o *LoadContext) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *LoadContext) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *LoadContext) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *LoadContext) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *LoadContext) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *LoadContext) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


