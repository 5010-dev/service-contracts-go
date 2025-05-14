# CryptoMarketContext

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Interval** | [**Interval**](Interval.md) |  | 
**MarketCategory** | **string** | Category of the market | 
**ExchangeType** | [**ExchangeType**](ExchangeType.md) |  | 
**Symbol** | [**Symbol**](Symbol.md) |  | 
**MarketType** | [**CryptoMarketType**](CryptoMarketType.md) |  | 

## Methods

### NewCryptoMarketContext

`func NewCryptoMarketContext(interval Interval, marketCategory string, exchangeType ExchangeType, symbol Symbol, marketType CryptoMarketType, ) *CryptoMarketContext`

NewCryptoMarketContext instantiates a new CryptoMarketContext object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCryptoMarketContextWithDefaults

`func NewCryptoMarketContextWithDefaults() *CryptoMarketContext`

NewCryptoMarketContextWithDefaults instantiates a new CryptoMarketContext object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInterval

`func (o *CryptoMarketContext) GetInterval() Interval`

GetInterval returns the Interval field if non-nil, zero value otherwise.

### GetIntervalOk

`func (o *CryptoMarketContext) GetIntervalOk() (*Interval, bool)`

GetIntervalOk returns a tuple with the Interval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterval

`func (o *CryptoMarketContext) SetInterval(v Interval)`

SetInterval sets Interval field to given value.


### GetMarketCategory

`func (o *CryptoMarketContext) GetMarketCategory() string`

GetMarketCategory returns the MarketCategory field if non-nil, zero value otherwise.

### GetMarketCategoryOk

`func (o *CryptoMarketContext) GetMarketCategoryOk() (*string, bool)`

GetMarketCategoryOk returns a tuple with the MarketCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarketCategory

`func (o *CryptoMarketContext) SetMarketCategory(v string)`

SetMarketCategory sets MarketCategory field to given value.


### GetExchangeType

`func (o *CryptoMarketContext) GetExchangeType() ExchangeType`

GetExchangeType returns the ExchangeType field if non-nil, zero value otherwise.

### GetExchangeTypeOk

`func (o *CryptoMarketContext) GetExchangeTypeOk() (*ExchangeType, bool)`

GetExchangeTypeOk returns a tuple with the ExchangeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchangeType

`func (o *CryptoMarketContext) SetExchangeType(v ExchangeType)`

SetExchangeType sets ExchangeType field to given value.


### GetSymbol

`func (o *CryptoMarketContext) GetSymbol() Symbol`

GetSymbol returns the Symbol field if non-nil, zero value otherwise.

### GetSymbolOk

`func (o *CryptoMarketContext) GetSymbolOk() (*Symbol, bool)`

GetSymbolOk returns a tuple with the Symbol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSymbol

`func (o *CryptoMarketContext) SetSymbol(v Symbol)`

SetSymbol sets Symbol field to given value.


### GetMarketType

`func (o *CryptoMarketContext) GetMarketType() CryptoMarketType`

GetMarketType returns the MarketType field if non-nil, zero value otherwise.

### GetMarketTypeOk

`func (o *CryptoMarketContext) GetMarketTypeOk() (*CryptoMarketType, bool)`

GetMarketTypeOk returns a tuple with the MarketType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarketType

`func (o *CryptoMarketContext) SetMarketType(v CryptoMarketType)`

SetMarketType sets MarketType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


