# \GroupApi

All URIs are relative to _https://hornet.snt.utwente.nl_

| Method                                                                                                                             | HTTP request                                            | Description                      |
| ---------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | -------------------------------- |
| [**delete_app_apicontrollers_committeeapi_deletecommittee**](GroupApi.md#delete_app_apicontrollers_committeeapi_deletecommittee)   | **DELETE** /api/group/{groupId}                         | Remove a group.                  |
| [**delete_app_apicontrollers_committeeapi_deletemember**](GroupApi.md#delete_app_apicontrollers_committeeapi_deletemember)         | **DELETE** /api/group/{groupId}/members/{groupMemberId} | Remove a group member.           |
| [**get_app_apicontrollers_committeeapi_get**](GroupApi.md#get_app_apicontrollers_committeeapi_get)                                 | **GET** /api/group                                      | Retrieve association group list. |
| [**get_app_apicontrollers_committeeapi_getcommittee**](GroupApi.md#get_app_apicontrollers_committeeapi_getcommittee)               | **GET** /api/group/{groupId}                            | Retrieve group.                  |
| [**get_app_apicontrollers_committeeapi_getmember**](GroupApi.md#get_app_apicontrollers_committeeapi_getmember)                     | **GET** /api/group/{groupId}/members/{groupMemberId}    | Retrieve group member.           |
| [**get_app_apicontrollers_committeeapi_getmembers**](GroupApi.md#get_app_apicontrollers_committeeapi_getmembers)                   | **GET** /api/group/{groupId}/members                    | Retrieve group members.          |
| [**post_app_apicontrollers_committeeapi_postcommittee**](GroupApi.md#post_app_apicontrollers_committeeapi_postcommittee)           | **POST** /api/group                                     | Add a group.                     |
| [**post_app_apicontrollers_committeeapi_postmember**](GroupApi.md#post_app_apicontrollers_committeeapi_postmember)                 | **POST** /api/group/{groupId}/members                   | Add a group member.              |
| [**put_app_apicontrollers_committeeapi_putcommittee**](GroupApi.md#put_app_apicontrollers_committeeapi_putcommittee)               | **PUT** /api/group/{groupId}                            | Update a group.                  |
| [**put_app_apicontrollers_committeeapi_putcommitteearchive**](GroupApi.md#put_app_apicontrollers_committeeapi_putcommitteearchive) | **PUT** /api/group/{groupId}/archive                    | Update the archive for a group.  |

## delete_app_apicontrollers_committeeapi_deletecommittee

> models::DeleteAppApicontrollersAssociationapiDeletemember200Response delete_app_apicontrollers_committeeapi_deletecommittee(group_id)
> Remove a group.

### Parameters

| Name         | Type    | Description | Required   | Notes |
| ------------ | ------- | ----------- | ---------- | ----- |
| **group_id** | **i32** | Group ID    | [required] |

### Return type

[**models::DeleteAppApicontrollersAssociationapiDeletemember200Response**](delete_app_apicontrollers_associationapi_deletemember_200_response.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## delete_app_apicontrollers_committeeapi_deletemember

> models::DeleteAppApicontrollersAssociationapiDeletemember200Response delete_app_apicontrollers_committeeapi_deletemember(group_id, group_member_id)
> Remove a group member.

### Parameters

| Name                | Type    | Description     | Required   | Notes |
| ------------------- | ------- | --------------- | ---------- | ----- |
| **group_id**        | **i32** | Group ID        | [required] |
| **group_member_id** | **i32** | Group member ID | [required] |

### Return type

[**models::DeleteAppApicontrollersAssociationapiDeletemember200Response**](delete_app_apicontrollers_associationapi_deletemember_200_response.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## get_app_apicontrollers_committeeapi_get

> Vec<models::Group> get_app_apicontrollers_committeeapi_get()
> Retrieve association group list.

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::Group>**](Group.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## get_app_apicontrollers_committeeapi_getcommittee

> models::Group get_app_apicontrollers_committeeapi_getcommittee(group_id)
> Retrieve group.

### Parameters

| Name         | Type    | Description | Required   | Notes |
| ------------ | ------- | ----------- | ---------- | ----- |
| **group_id** | **i32** | Group ID    | [required] |

### Return type

[**models::Group**](Group.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## get_app_apicontrollers_committeeapi_getmember

> models::GroupMember get_app_apicontrollers_committeeapi_getmember(group_id, group_member_id)
> Retrieve group member.

### Parameters

| Name                | Type    | Description     | Required   | Notes |
| ------------------- | ------- | --------------- | ---------- | ----- |
| **group_id**        | **i32** | Group ID        | [required] |
| **group_member_id** | **i32** | Group member ID | [required] |

### Return type

[**models::GroupMember**](GroupMember.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## get_app_apicontrollers_committeeapi_getmembers

> Vec<models::GroupMember> get_app_apicontrollers_committeeapi_getmembers(group_id)
> Retrieve group members.

### Parameters

| Name         | Type    | Description | Required   | Notes |
| ------------ | ------- | ----------- | ---------- | ----- |
| **group_id** | **i32** | Group ID    | [required] |

### Return type

[**Vec<models::GroupMember>**](GroupMember.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## post_app_apicontrollers_committeeapi_postcommittee

> models::Group post_app_apicontrollers_committeeapi_postcommittee(create_group)
> Add a group.

### Parameters

| Name             | Type                                      | Description | Required | Notes |
| ---------------- | ----------------------------------------- | ----------- | -------- | ----- |
| **create_group** | Option<[**CreateGroup**](CreateGroup.md)> |             |          |

### Return type

[**models::Group**](Group.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## post_app_apicontrollers_committeeapi_postmember

> models::GroupMember post_app_apicontrollers_committeeapi_postmember(group_id, new_group_member)
> Add a group member.

### Parameters

| Name                 | Type                                            | Description | Required   | Notes |
| -------------------- | ----------------------------------------------- | ----------- | ---------- | ----- |
| **group_id**         | **i32**                                         | Group ID    | [required] |
| **new_group_member** | Option<[**NewGroupMember**](NewGroupMember.md)> |             |            |

### Return type

[**models::GroupMember**](GroupMember.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## put_app_apicontrollers_committeeapi_putcommittee

> models::Group put_app_apicontrollers_committeeapi_putcommittee(group_id, update_group)
> Update a group.

### Parameters

| Name             | Type                                      | Description | Required   | Notes |
| ---------------- | ----------------------------------------- | ----------- | ---------- | ----- |
| **group_id**     | **i32**                                   | Group ID    | [required] |
| **update_group** | Option<[**UpdateGroup**](UpdateGroup.md)> |             |            |

### Return type

[**models::Group**](Group.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

## put_app_apicontrollers_committeeapi_putcommitteearchive

> models::Group put_app_apicontrollers_committeeapi_putcommitteearchive(group_id, update_group_archive)
> Update the archive for a group.

Note that when you disable an archive, all e-mails in it will be lost!

### Parameters

| Name                     | Type                                                    | Description | Required   | Notes |
| ------------------------ | ------------------------------------------------------- | ----------- | ---------- | ----- |
| **group_id**             | **i32**                                                 | Group ID    | [required] |
| **update_group_archive** | Option<[**UpdateGroupArchive**](UpdateGroupArchive.md)> |             |            |

### Return type

[**models::Group**](Group.md)

### Authorization

[QueryAuth](../README.md#QueryAuth), [HeaderAuth](../README.md#HeaderAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)
