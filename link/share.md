## Share Fields
| Name               | Type           | Optional | Description                                         |
| ------------------ | -------------- | -------- | --------------------------------------- |
| share_id           | string         | y        | Parent share id.                        |
| likes_total        | integer        | n        | Total likes number.                     |
| comments_total     | integer        | n        | Total comments number.                  |
| shares_total       | integer        | n        | Total shares number.                    |
| pst_total          | big integer    | n        | Total PST earned.                       |
| pst_updated        | integer        | n        | Last PST updated time. Unix timestamp.  |
| is_liked           | bool           | y        | Whether current account liked this share.|
| content            | entity_id      | n        | Share related content.                  |
| report             | entity_id      | y        | Report metadata.                        |
| hp                 | integer        | n        | hp value.                               |