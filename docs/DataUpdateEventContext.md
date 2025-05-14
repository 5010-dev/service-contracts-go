# DataUpdateEventContext

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExchangeType** | **string** |  | 
**Symbol** | **string** |  | 
**Interval** | **string** |  | 

## Methods

### NewDataUpdateEventContext

`func NewDataUpdateEventContext(exchangeType string, symbol string, interval string, ) *DataUpdateEventContext`

NewDataUpdateEventContext instantiates a new DataUpdateEventContext object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDataUpdateEventContextWithDefaults

`func NewDataUpdateEventContextWithDefaults() *DataUpdateEventContext`

NewDataUpdateEventContextWithDefaults instantiates a new DataUpdateEventContext object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExchangeType

`func (o *DataUpdateEventContext) GetExchangeType() string`

GetExchangeType returns the ExchangeType field if non-nil, zero value otherwise.

### GetExchangeTypeOk

`func (o *DataUpdateEventContext) GetExchangeTypeOk() (*string, bool)`

GetExchangeTypeOk returns a tuple with the ExchangeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeType

`func (o *DataUpdateEventContext) SetExchangeType(v string)`

SetExchangeType sets ExchangeType field to given value.


### GetSymbol

`func (o *DataUpdateEventContext) GetSymbol() string`

GetSymbol returns the Symbol field if non-nil, zero value otherwise.

### GetSymbolOk

`func (o *DataUpdateEventContext) GetSymbolOk() (*string, bool)`

GetSymbolOk returns a tuple with the Symbol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSymbol

`func (o *DataUpdateEventContext) SetSymbol(v string)`

SetSymbol sets Symbol field to given value.


### GetInterval

`func (o *DataUpdateEventContext) GetInterval() string`

GetInterval returns the Interval field if non-nil, zero value otherwise.

### GetIntervalOk

`func (o *DataUpdateEventContext) GetIntervalOk() (*string, bool)`

GetIntervalOk returns a tuple with the Interval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterval

`func (o *DataUpdateEventContext) SetInterval(v string)`

SetInterval sets Interval field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


