## Logistics Fields

| Name            | Type           | Optional | Description
| --------------- | -------------- | -------- | -----------
| order_no        | string         |          | 订单号
| bl_no           | string         |          | 提单号
| origin_country  | string         |          | 出发国家
| origin_address  | string         |          | 出发地址
| dest_country    | string         |          | 目的国家
| dest_address    | string         |          | 目的地址
| order_type      | string         |          | 订单类型,可选
| transport_type  | string         |          | 物流运输类型(空运，水运，陆运，...)
| company         | string         |          | 物流公司
| tracks          | array(string)  |          | 物流轨迹描述
| status          | string         |          | 物流状态
| time            | string         |          | 操作时间