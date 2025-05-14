# BaseMarketContext

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Interval** | [**Interval**](Interval.md) |  | 
**MarketCategory** | **string** | Category of the market | 

## Methods

### NewBaseMarketContext

`func NewBaseMarketContext(interval Interval, marketCategory string, ) *BaseMarketContext`

NewBaseMarketContext instantiates a new BaseMarketContext object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBaseMarketContextWithDefaults

`func NewBaseMarketContextWithDefaults() *BaseMarketContext`

NewBaseMarketContextWithDefaults instantiates a new BaseMarketContext object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInterval

`func (o *BaseMarketContext) GetInterval() Interval`

GetInterval returns the Interval field if non-nil, zero value otherwise.

### GetIntervalOk

`func (o *BaseMarketContext) GetIntervalOk() (*Interval, bool)`

GetIntervalOk returns a tuple with the Interval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterval

`func (o *BaseMarketContext) SetInterval(v Interval)`

SetInterval sets Interval field to given value.


### GetMarketCategory

`func (o *BaseMarketContext) GetMarketCategory() string`

GetMarketCategory returns the MarketCategory field if non-nil, zero value otherwise.

### GetMarketCategoryOk

`func (o *BaseMarketContext) GetMarketCategoryOk() (*string, bool)`

GetMarketCategoryOk returns a tuple with the MarketCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarketCategory

`func (o *BaseMarketContext) SetMarketCategory(v string)`

SetMarketCategory sets MarketCategory field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


