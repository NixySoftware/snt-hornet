# AssociationMember

## Properties

| Name                  | Type                                    | Description                                            | Notes                        |
| --------------------- | --------------------------------------- | ------------------------------------------------------ | ---------------------------- |
| **admin**             | Option<**bool**>                        |                                                        | [optional][default to false] |
| **id**                | Option<**i32**>                         |                                                        | [optional]                   |
| **internal_email**    | Option<**String**>                      | This is equals the internalUsername @ domain           | [optional]                   |
| **internal_username** | **String**                              |                                                        | [readonly]                   |
| **mail_size**         | Option<**String**>                      | Saved as string, convert to bytes using SizeConverter. | [optional]                   |
| **user**              | Option<[**models::Member**](Member.md)> |                                                        | [optional]                   |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
