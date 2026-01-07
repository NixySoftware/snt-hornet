# \AssociationApi

All URIs are relative to _https://hornet.snt.utwente.nl_

| Method                                                                                                                               | HTTP request                                              | Description                               |
| ------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------- | ----------------------------------------- |
| [**delete_app_apicontrollers_associationapi_deletemember**](AssociationApi.md#delete_app_apicontrollers_associationapi_deletemember) | **DELETE** /api/association/members/{associationMemberId} | Remove a member from the association.     |
| [**get_app_apicontrollers_associationapi_get**](AssociationApi.md#get_app_apicontrollers_associationapi_get)                         | **GET** /api/association                                  | Retrieve general association information. |
| [**get_app_apicontrollers_associationapi_getmember**](AssociationApi.md#get_app_apicontrollers_associationapi_getmember)             | **GET** /api/association/members/{associationMemberId}    | Get an association member.                |
| [**get_app_apicontrollers_associationapi_getmembers**](AssociationApi.md#get_app_apicontrollers_associationapi_getmembers)           | **GET** /api/association/members                          | Retrieve association members.             |
| [**post_app_apicontrollers_associationapi_postmember**](AssociationApi.md#post_app_apicontrollers_associationapi_postmember)         | **POST** /api/association/members                         | Add a member to the association.          |
| [**put_app_apicontrollers_associationapi_put**](AssociationApi.md#put_app_apicontrollers_associationapi_put)                         | **PUT** /api/association                                  | Update general association information.   |
| [**put_app_apicontrollers_associationapi_putmember**](AssociationApi.md#put_app_apicontrollers_associationapi_putmember)             | **PUT** /api/association/members/{associationMemberId}    | Update an association member.             |

## delete_app_apicontrollers_associationapi_deletemember

> models::DeleteAppApicontrollersAssociationapiDeletemember200Response delete_app_apicontrollers_associationapi_deletemember(association_member_id)
> Remove a member from the association.

### Parameters

| Name                      | Type    | Description           | Required   | Notes |
| ------------------------- | ------- | --------------------- | ---------- | ----- |
| **association_member_id** | **i32** | Association member ID | [required] |

### Return type

[**models::DeleteAppApicontrollersAssociationapiDeletemember200Response**](delete_app_apicontrollers_associationapi_deletemember_200_response.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## get_app_apicontrollers_associationapi_get

> models::Association get_app_apicontrollers_associationapi_get()
> Retrieve general association information.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::Association**](Association.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## get_app_apicontrollers_associationapi_getmember

> models::AssociationMember get_app_apicontrollers_associationapi_getmember(association_member_id)
> Get an association member.

### Parameters

| Name                      | Type    | Description           | Required   | Notes |
| ------------------------- | ------- | --------------------- | ---------- | ----- |
| **association_member_id** | **i32** | Association member ID | [required] |

### Return type

[**models::AssociationMember**](AssociationMember.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## get_app_apicontrollers_associationapi_getmembers

> Vec<models::AssociationMember> get_app_apicontrollers_associationapi_getmembers()
> Retrieve association members.

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::AssociationMember>**](AssociationMember.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## post_app_apicontrollers_associationapi_postmember

> models::AssociationMember post_app_apicontrollers_associationapi_postmember(create_association_member)
> Add a member to the association.

### Parameters

| Name                          | Type                                                              | Description | Required | Notes |
| ----------------------------- | ----------------------------------------------------------------- | ----------- | -------- | ----- |
| **create_association_member** | Option<[**CreateAssociationMember**](CreateAssociationMember.md)> |             |          |

### Return type

[**models::AssociationMember**](AssociationMember.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## put_app_apicontrollers_associationapi_put

> models::Association put_app_apicontrollers_associationapi_put(update_association)
> Update general association information.

### Parameters

| Name                   | Type                                                  | Description | Required | Notes |
| ---------------------- | ----------------------------------------------------- | ----------- | -------- | ----- |
| **update_association** | Option<[**UpdateAssociation**](UpdateAssociation.md)> |             |          |

### Return type

[**models::Association**](Association.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## put_app_apicontrollers_associationapi_putmember

> models::AssociationMember put_app_apicontrollers_associationapi_putmember(association_member_id, update_association_member)
> Update an association member.

### Parameters

| Name                          | Type                                                              | Description           | Required   | Notes |
| ----------------------------- | ----------------------------------------------------------------- | --------------------- | ---------- | ----- |
| **association_member_id**     | **i32**                                                           | Association member ID | [required] |
| **update_association_member** | Option<[**UpdateAssociationMember**](UpdateAssociationMember.md)> |                       |            |

### Return type

[**models::AssociationMember**](AssociationMember.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)
