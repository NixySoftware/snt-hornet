# Association

## Properties

| Name                                | Type               | Description                                            | Notes                               |
| ----------------------------------- | ------------------ | ------------------------------------------------------ | ----------------------------------- |
| **contact_email_address**           | **String**         |                                                        |
| **default_emailbox_size**           | Option<**String**> | Saved as string, convert to bytes using SizeConverter. | [optional][default to 100M]         |
| **detected_storage_size**           | Option<**i32**>    |                                                        | [optional][readonly]                |
| **domain**                          | **String**         |                                                        | [readonly]                          |
| **full_name**                       | **String**         |                                                        |
| **id**                              | Option<**i32**>    |                                                        | [optional]                          |
| **storage_size**                    | Option<**String**> | Saved as string, convert to bytes using SizeConverter. | [optional][readonly][default to 1G] |
| **technical_contact_email_address** | **String**         |                                                        |
| **web_email_size**                  | Option<**String**> | Saved as string, convert to bytes using SizeConverter. | [optional][readonly][default to 1G] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
