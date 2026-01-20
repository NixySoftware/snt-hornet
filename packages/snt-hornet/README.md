# Rust OpenAPI client for SNT Hornet

The Hornet API can be used to programmatically update exposed association data.

For more information, visit https://hornet.snt.utwente.nl/en/api.

## Installation

```shell
cargo add snt-hornet
```

## Documentation

Documentation for is available on [Docs.rs](https://docs.rs/snt-hornet/latest/snt_hornet/).

### Documentation for API Endpoints

All URIs are relative to _https://hornet.snt.utwente.nl_

| Class            | Method                                                                                                                                    | HTTP request                                              | Description                               |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- | ----------------------------------------- |
| _AssociationApi_ | [**delete_app_apicontrollers_associationapi_deletemember**](docs/AssociationApi.md#delete_app_apicontrollers_associationapi_deletemember) | **DELETE** /api/association/members/{associationMemberId} | Remove a member from the association.     |
| _AssociationApi_ | [**get_app_apicontrollers_associationapi_get**](docs/AssociationApi.md#get_app_apicontrollers_associationapi_get)                         | **GET** /api/association                                  | Retrieve general association information. |
| _AssociationApi_ | [**get_app_apicontrollers_associationapi_getmember**](docs/AssociationApi.md#get_app_apicontrollers_associationapi_getmember)             | **GET** /api/association/members/{associationMemberId}    | Get an association member.                |
| _AssociationApi_ | [**get_app_apicontrollers_associationapi_getmembers**](docs/AssociationApi.md#get_app_apicontrollers_associationapi_getmembers)           | **GET** /api/association/members                          | Retrieve association members.             |
| _AssociationApi_ | [**post_app_apicontrollers_associationapi_postmember**](docs/AssociationApi.md#post_app_apicontrollers_associationapi_postmember)         | **POST** /api/association/members                         | Add a member to the association.          |
| _AssociationApi_ | [**put_app_apicontrollers_associationapi_put**](docs/AssociationApi.md#put_app_apicontrollers_associationapi_put)                         | **PUT** /api/association                                  | Update general association information.   |
| _AssociationApi_ | [**put_app_apicontrollers_associationapi_putmember**](docs/AssociationApi.md#put_app_apicontrollers_associationapi_putmember)             | **PUT** /api/association/members/{associationMemberId}    | Update an association member.             |
| _GroupApi_       | [**delete_app_apicontrollers_committeeapi_deletecommittee**](docs/GroupApi.md#delete_app_apicontrollers_committeeapi_deletecommittee)     | **DELETE** /api/group/{groupId}                           | Remove a group.                           |
| _GroupApi_       | [**delete_app_apicontrollers_committeeapi_deletemember**](docs/GroupApi.md#delete_app_apicontrollers_committeeapi_deletemember)           | **DELETE** /api/group/{groupId}/members/{groupMemberId}   | Remove a group member.                    |
| _GroupApi_       | [**get_app_apicontrollers_committeeapi_get**](docs/GroupApi.md#get_app_apicontrollers_committeeapi_get)                                   | **GET** /api/group                                        | Retrieve association group list.          |
| _GroupApi_       | [**get_app_apicontrollers_committeeapi_getcommittee**](docs/GroupApi.md#get_app_apicontrollers_committeeapi_getcommittee)                 | **GET** /api/group/{groupId}                              | Retrieve group.                           |
| _GroupApi_       | [**get_app_apicontrollers_committeeapi_getmember**](docs/GroupApi.md#get_app_apicontrollers_committeeapi_getmember)                       | **GET** /api/group/{groupId}/members/{groupMemberId}      | Retrieve group member.                    |
| _GroupApi_       | [**get_app_apicontrollers_committeeapi_getmembers**](docs/GroupApi.md#get_app_apicontrollers_committeeapi_getmembers)                     | **GET** /api/group/{groupId}/members                      | Retrieve group members.                   |
| _GroupApi_       | [**post_app_apicontrollers_committeeapi_postcommittee**](docs/GroupApi.md#post_app_apicontrollers_committeeapi_postcommittee)             | **POST** /api/group                                       | Add a group.                              |
| _GroupApi_       | [**post_app_apicontrollers_committeeapi_postmember**](docs/GroupApi.md#post_app_apicontrollers_committeeapi_postmember)                   | **POST** /api/group/{groupId}/members                     | Add a group member.                       |
| _GroupApi_       | [**put_app_apicontrollers_committeeapi_putcommittee**](docs/GroupApi.md#put_app_apicontrollers_committeeapi_putcommittee)                 | **PUT** /api/group/{groupId}                              | Update a group.                           |
| _GroupApi_       | [**put_app_apicontrollers_committeeapi_putcommitteearchive**](docs/GroupApi.md#put_app_apicontrollers_committeeapi_putcommitteearchive)   | **PUT** /api/group/{groupId}/archive                      | Update the archive for a group.           |

### Documentation For Models

- [Association](docs/Association.md)
- [AssociationMember](docs/AssociationMember.md)
- [CreateAssociationMember](docs/CreateAssociationMember.md)
- [CreateGroup](docs/CreateGroup.md)
- [DeleteAppApicontrollersAssociationapiDeletemember200Response](docs/DeleteAppApicontrollersAssociationapiDeletemember200Response.md)
- [Group](docs/Group.md)
- [GroupMember](docs/GroupMember.md)
- [Member](docs/Member.md)
- [NewGroupMember](docs/NewGroupMember.md)
- [PutAppApicontrollersAssociationapiPut400Response](docs/PutAppApicontrollersAssociationapiPut400Response.md)
- [PutAppApicontrollersAssociationapiPut400ResponseErrorsInner](docs/PutAppApicontrollersAssociationapiPut400ResponseErrorsInner.md)
- [UpdateAssociation](docs/UpdateAssociation.md)
- [UpdateAssociationMember](docs/UpdateAssociationMember.md)
- [UpdateGroup](docs/UpdateGroup.md)
- [UpdateGroupArchive](docs/UpdateGroupArchive.md)

## License

This project is available under the [MIT license](../../LICENSE.md).
