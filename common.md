## Common Fields

| Name               | Type           | Optional | Description                                         |
| ------------------ | -------------- | -------- | --------------------------------------- |
| version            | string         | n        | DTCP version. "1.0" for now.            |
| type               | string         | n        | Metadata type. "entity" or "link".      |
| tag                | string         | n        | Entity or link type such as "Article".  |
| created            | integer        | n     
| updated            | integer        | n
| status             | string         | n        | "created", "updated" or "deleted".      |    
| dna                | string         | n
| creator            | entity_id      | n
| signature          | string         | n
| id                 | string         | y
| parent_dna         | string         | y
| extra              | map            | y
| transaction        | entity_id      | y


## Entity Common Fields

| Name               | Type           | Optional | Description                                         |
| ------------------ | -------------- | -------- | --------------------------------------- |
| title              | string         | n        | Title. |
| description        | string         | n        |


## Link Common Fields

| Name               | Type           | Optional | Description                                         |
| ------------------ | -------------- | -------- | --------------------------------------- |
| src                | entity_id      |
| dest               | entity_id      |
