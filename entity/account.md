## Account Fields

| Name                | Type    | Optional | Description |
| --------------      | ------- | -------- | ---------------------------------------- |
| address             | string  | n        | Account address. |
| title               | string  | n        | Account name. |
| abstract            | string  | y        | Description. |
| avatar              | string  | y        | An image id used for avatar. |
| creator             | object  | y        | Creator of the [sub account](./dtcp.md#sub-accounts). |
| created             | integer | n        | Account creation time. Unix timestamp. |
| updated             | integer | n        | Account last updating time. Unix timestamp. |
| extra               | object  | y        | Extra metadata. |
| signature           | string  | n        | [Metadata signature](./dtcp.md#metadata-signature). |
| dna                 | string  | n        | DNA of the account. |
| hp                  | integer | n        | available hp value. |
| total_hp            | integer | n        | total hp value. |
| credits             | integer | n        | Current credits. |
| transaction_id      | string  | n        | Latest transaction id. |