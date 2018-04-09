---
title: Delete Customization
permalink: /reference/rest-api/customizations_delete
---

To remove customization, send a DELETE request to /api/user/customizations/:customization_id

**HTTP request**

DELETE /api/user/customizations/:customization_id

**Parameters**

| Parameter               | Type   | Description                    | Required | Notes |
| ----------------------- | ------ | ------------------------------ | -------- | ----- |
| form_configuration_name | String | Name of the form configuration | Required |       |

**Example request**

{% include reference/request_headers.md %}

```
{
  "form_configuration_name": "reference_rest_api_delete_customizations"
}
```

| Element                 | Type   | Description                           | Required? |
| ----------------------- | ------ | ------------------------------------- | --------- |
| form_configuration_name | String | Name of the defined FormConfiguration | Required  |

**Example response**

{% include reference/response_headers.md %}

```

```

| Element                             | Type                                       | Description                                                    |
| ----------------------------------- | ------------------------------------------ | -------------------------------------------------------------- |
| [Element as it appears in response] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents] |
| […]                                 | […]                                        | […]                                                            |

{% include reference/error_and_status_codes_delete.md %}