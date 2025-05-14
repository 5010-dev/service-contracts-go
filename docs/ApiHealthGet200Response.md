# ApiHealthGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** |  | [optional] 
**Role** | Pointer to **string** |  | [optional] 
**Time** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewApiHealthGet200Response

`func NewApiHealthGet200Response() *ApiHealthGet200Response`

NewApiHealthGet200Response instantiates a new ApiHealthGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiHealthGet200ResponseWithDefaults

`func NewApiHealthGet200ResponseWithDefaults() *ApiHealthGet200Response`

NewApiHealthGet200ResponseWithDefaults instantiates a new ApiHealthGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *ApiHealthGet200Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ApiHealthGet200Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ApiHealthGet200Response) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ApiHealthGet200Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetRole

`func (o *ApiHealthGet200Response) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *ApiHealthGet200Response) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *ApiHealthGet200Response) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *ApiHealthGet200Response) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetTime

`func (o *ApiHealthGet200Response) GetTime() time.Time`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *ApiHealthGet200Response) GetTimeOk() (*time.Time, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *ApiHealthGet200Response) SetTime(v time.Time)`

SetTime sets Time field to given value.

### HasTime

`func (o *ApiHealthGet200Response) HasTime() bool`

HasTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


