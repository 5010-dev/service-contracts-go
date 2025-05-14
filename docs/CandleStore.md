# CandleStore

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Candles** | [**[]Candle**](Candle.md) |  | 
**LastUpdated** | Pointer to **NullableTime** |  | [optional] 
**NextUpdate** | **time.Time** |  | 

## Methods

### NewCandleStore

`func NewCandleStore(candles []Candle, nextUpdate time.Time, ) *CandleStore`

NewCandleStore instantiates a new CandleStore object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCandleStoreWithDefaults

`func NewCandleStoreWithDefaults() *CandleStore`

NewCandleStoreWithDefaults instantiates a new CandleStore object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCandles

`func (o *CandleStore) GetCandles() []Candle`

GetCandles returns the Candles field if non-nil, zero value otherwise.

### GetCandlesOk

`func (o *CandleStore) GetCandlesOk() (*[]Candle, bool)`

GetCandlesOk returns a tuple with the Candles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCandles

`func (o *CandleStore) SetCandles(v []Candle)`

SetCandles sets Candles field to given value.


### GetLastUpdated

`func (o *CandleStore) GetLastUpdated() time.Time`

GetLastUpdated returns the LastUpdated field if non-nil, zero value otherwise.

### GetLastUpdatedOk

`func (o *CandleStore) GetLastUpdatedOk() (*time.Time, bool)`

GetLastUpdatedOk returns a tuple with the LastUpdated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdated

`func (o *CandleStore) SetLastUpdated(v time.Time)`

SetLastUpdated sets LastUpdated field to given value.

### HasLastUpdated

`func (o *CandleStore) HasLastUpdated() bool`

HasLastUpdated returns a boolean if a field has been set.

### SetLastUpdatedNil

`func (o *CandleStore) SetLastUpdatedNil(b bool)`

 SetLastUpdatedNil sets the value for LastUpdated to be an explicit nil

### UnsetLastUpdated
`func (o *CandleStore) UnsetLastUpdated()`

UnsetLastUpdated ensures that no value is present for LastUpdated, not even an explicit nil
### GetNextUpdate

`func (o *CandleStore) GetNextUpdate() time.Time`

GetNextUpdate returns the NextUpdate field if non-nil, zero value otherwise.

### GetNextUpdateOk

`func (o *CandleStore) GetNextUpdateOk() (*time.Time, bool)`

GetNextUpdateOk returns a tuple with the NextUpdate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextUpdate

`func (o *CandleStore) SetNextUpdate(v time.Time)`

SetNextUpdate sets NextUpdate field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


