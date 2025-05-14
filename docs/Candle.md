# Candle

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Timestamp** | **int64** | Unix timestamp in milliseconds | 
**Open** | **float64** | Opening price | 
**High** | **float64** | Highest price | 
**Low** | **float64** | Lowest price | 
**Close** | **float64** | Closing price | 
**Volume** | **float64** | Trading volume | 

## Methods

### NewCandle

`func NewCandle(timestamp int64, open float64, high float64, low float64, close float64, volume float64, ) *Candle`

NewCandle instantiates a new Candle object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCandleWithDefaults

`func NewCandleWithDefaults() *Candle`

NewCandleWithDefaults instantiates a new Candle object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTimestamp

`func (o *Candle) GetTimestamp() int64`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *Candle) GetTimestampOk() (*int64, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *Candle) SetTimestamp(v int64)`

SetTimestamp sets Timestamp field to given value.


### GetOpen

`func (o *Candle) GetOpen() float64`

GetOpen returns the Open field if non-nil, zero value otherwise.

### GetOpenOk

`func (o *Candle) GetOpenOk() (*float64, bool)`

GetOpenOk returns a tuple with the Open field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpen

`func (o *Candle) SetOpen(v float64)`

SetOpen sets Open field to given value.


### GetHigh

`func (o *Candle) GetHigh() float64`

GetHigh returns the High field if non-nil, zero value otherwise.

### GetHighOk

`func (o *Candle) GetHighOk() (*float64, bool)`

GetHighOk returns a tuple with the High field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHigh

`func (o *Candle) SetHigh(v float64)`

SetHigh sets High field to given value.


### GetLow

`func (o *Candle) GetLow() float64`

GetLow returns the Low field if non-nil, zero value otherwise.

### GetLowOk

`func (o *Candle) GetLowOk() (*float64, bool)`

GetLowOk returns a tuple with the Low field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLow

`func (o *Candle) SetLow(v float64)`

SetLow sets Low field to given value.


### GetClose

`func (o *Candle) GetClose() float64`

GetClose returns the Close field if non-nil, zero value otherwise.

### GetCloseOk

`func (o *Candle) GetCloseOk() (*float64, bool)`

GetCloseOk returns a tuple with the Close field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClose

`func (o *Candle) SetClose(v float64)`

SetClose sets Close field to given value.


### GetVolume

`func (o *Candle) GetVolume() float64`

GetVolume returns the Volume field if non-nil, zero value otherwise.

### GetVolumeOk

`func (o *Candle) GetVolumeOk() (*float64, bool)`

GetVolumeOk returns a tuple with the Volume field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVolume

`func (o *Candle) SetVolume(v float64)`

SetVolume sets Volume field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


