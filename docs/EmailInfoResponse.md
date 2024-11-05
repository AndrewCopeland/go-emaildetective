# EmailInfoResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** |  | 
**User** | **string** |  | 
**Domain** | **string** |  | 
**ValidEmail** | **bool** |  | 
**ValidSpf** | **bool** |  | 
**ValidDmarc** | **bool** |  | 
**ValidMx** | **bool** |  | 
**ValidTld** | **bool** |  | 
**Nonsense** | **bool** |  | 
**Role** | **bool** |  | 
**Free** | **bool** |  | 
**Disposable** | **bool** |  | 
**Score** | **int32** |  | 
**SuspicionRating** | **string** |  | 

## Methods

### NewEmailInfoResponse

`func NewEmailInfoResponse(email string, user string, domain string, validEmail bool, validSpf bool, validDmarc bool, validMx bool, validTld bool, nonsense bool, role bool, free bool, disposable bool, score int32, suspicionRating string, ) *EmailInfoResponse`

NewEmailInfoResponse instantiates a new EmailInfoResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmailInfoResponseWithDefaults

`func NewEmailInfoResponseWithDefaults() *EmailInfoResponse`

NewEmailInfoResponseWithDefaults instantiates a new EmailInfoResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *EmailInfoResponse) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *EmailInfoResponse) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *EmailInfoResponse) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetUser

`func (o *EmailInfoResponse) GetUser() string`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *EmailInfoResponse) GetUserOk() (*string, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *EmailInfoResponse) SetUser(v string)`

SetUser sets User field to given value.


### GetDomain

`func (o *EmailInfoResponse) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *EmailInfoResponse) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *EmailInfoResponse) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetValidEmail

`func (o *EmailInfoResponse) GetValidEmail() bool`

GetValidEmail returns the ValidEmail field if non-nil, zero value otherwise.

### GetValidEmailOk

`func (o *EmailInfoResponse) GetValidEmailOk() (*bool, bool)`

GetValidEmailOk returns a tuple with the ValidEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidEmail

`func (o *EmailInfoResponse) SetValidEmail(v bool)`

SetValidEmail sets ValidEmail field to given value.


### GetValidSpf

`func (o *EmailInfoResponse) GetValidSpf() bool`

GetValidSpf returns the ValidSpf field if non-nil, zero value otherwise.

### GetValidSpfOk

`func (o *EmailInfoResponse) GetValidSpfOk() (*bool, bool)`

GetValidSpfOk returns a tuple with the ValidSpf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidSpf

`func (o *EmailInfoResponse) SetValidSpf(v bool)`

SetValidSpf sets ValidSpf field to given value.


### GetValidDmarc

`func (o *EmailInfoResponse) GetValidDmarc() bool`

GetValidDmarc returns the ValidDmarc field if non-nil, zero value otherwise.

### GetValidDmarcOk

`func (o *EmailInfoResponse) GetValidDmarcOk() (*bool, bool)`

GetValidDmarcOk returns a tuple with the ValidDmarc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidDmarc

`func (o *EmailInfoResponse) SetValidDmarc(v bool)`

SetValidDmarc sets ValidDmarc field to given value.


### GetValidMx

`func (o *EmailInfoResponse) GetValidMx() bool`

GetValidMx returns the ValidMx field if non-nil, zero value otherwise.

### GetValidMxOk

`func (o *EmailInfoResponse) GetValidMxOk() (*bool, bool)`

GetValidMxOk returns a tuple with the ValidMx field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidMx

`func (o *EmailInfoResponse) SetValidMx(v bool)`

SetValidMx sets ValidMx field to given value.


### GetValidTld

`func (o *EmailInfoResponse) GetValidTld() bool`

GetValidTld returns the ValidTld field if non-nil, zero value otherwise.

### GetValidTldOk

`func (o *EmailInfoResponse) GetValidTldOk() (*bool, bool)`

GetValidTldOk returns a tuple with the ValidTld field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidTld

`func (o *EmailInfoResponse) SetValidTld(v bool)`

SetValidTld sets ValidTld field to given value.


### GetNonsense

`func (o *EmailInfoResponse) GetNonsense() bool`

GetNonsense returns the Nonsense field if non-nil, zero value otherwise.

### GetNonsenseOk

`func (o *EmailInfoResponse) GetNonsenseOk() (*bool, bool)`

GetNonsenseOk returns a tuple with the Nonsense field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonsense

`func (o *EmailInfoResponse) SetNonsense(v bool)`

SetNonsense sets Nonsense field to given value.


### GetRole

`func (o *EmailInfoResponse) GetRole() bool`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *EmailInfoResponse) GetRoleOk() (*bool, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *EmailInfoResponse) SetRole(v bool)`

SetRole sets Role field to given value.


### GetFree

`func (o *EmailInfoResponse) GetFree() bool`

GetFree returns the Free field if non-nil, zero value otherwise.

### GetFreeOk

`func (o *EmailInfoResponse) GetFreeOk() (*bool, bool)`

GetFreeOk returns a tuple with the Free field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFree

`func (o *EmailInfoResponse) SetFree(v bool)`

SetFree sets Free field to given value.


### GetDisposable

`func (o *EmailInfoResponse) GetDisposable() bool`

GetDisposable returns the Disposable field if non-nil, zero value otherwise.

### GetDisposableOk

`func (o *EmailInfoResponse) GetDisposableOk() (*bool, bool)`

GetDisposableOk returns a tuple with the Disposable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisposable

`func (o *EmailInfoResponse) SetDisposable(v bool)`

SetDisposable sets Disposable field to given value.


### GetScore

`func (o *EmailInfoResponse) GetScore() int32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *EmailInfoResponse) GetScoreOk() (*int32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *EmailInfoResponse) SetScore(v int32)`

SetScore sets Score field to given value.


### GetSuspicionRating

`func (o *EmailInfoResponse) GetSuspicionRating() string`

GetSuspicionRating returns the SuspicionRating field if non-nil, zero value otherwise.

### GetSuspicionRatingOk

`func (o *EmailInfoResponse) GetSuspicionRatingOk() (*string, bool)`

GetSuspicionRatingOk returns a tuple with the SuspicionRating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuspicionRating

`func (o *EmailInfoResponse) SetSuspicionRating(v string)`

SetSuspicionRating sets SuspicionRating field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


