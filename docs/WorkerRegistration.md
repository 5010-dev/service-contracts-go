# WorkerRegistration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Exchanges** | [**[]ExchangeType**](ExchangeType.md) |  | 
**Capacity** | **int32** |  | 
**ApiUrl** | **string** |  | 

## Methods

### NewWorkerRegistration

`func NewWorkerRegistration(id string, exchanges []ExchangeType, capacity int32, apiUrl string, ) *WorkerRegistration`

NewWorkerRegistration instantiates a new WorkerRegistration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkerRegistrationWithDefaults

`func NewWorkerRegistrationWithDefaults() *WorkerRegistration`

NewWorkerRegistrationWithDefaults instantiates a new WorkerRegistration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WorkerRegistration) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkerRegistration) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkerRegistration) SetId(v string)`

SetId sets Id field to given value.


### GetExchanges

`func (o *WorkerRegistration) GetExchanges() []ExchangeType`

GetExchanges returns the Exchanges field if non-nil, zero value otherwise.

### GetExchangesOk

`func (o *WorkerRegistration) GetExchangesOk() (*[]ExchangeType, bool)`

GetExchangesOk returns a tuple with the Exchanges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExchanges

`func (o *WorkerRegistration) SetExchanges(v []ExchangeType)`

SetExchanges sets Exchanges field to given value.


### GetCapacity

`func (o *WorkerRegistration) GetCapacity() int32`

GetCapacity returns the Capacity field if non-nil, zero value otherwise.

### GetCapacityOk

`func (o *WorkerRegistration) GetCapacityOk() (*int32, bool)`

GetCapacityOk returns a tuple with the Capacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapacity

`func (o *WorkerRegistration) SetCapacity(v int32)`

SetCapacity sets Capacity field to given value.


### GetApiUrl

`func (o *WorkerRegistration) GetApiUrl() string`

GetApiUrl returns the ApiUrl field if non-nil, zero value otherwise.

### GetApiUrlOk

`func (o *WorkerRegistration) GetApiUrlOk() (*string, bool)`

GetApiUrlOk returns a tuple with the ApiUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiUrl

`func (o *WorkerRegistration) SetApiUrl(v string)`

SetApiUrl sets ApiUrl field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


