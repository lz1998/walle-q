# 消息 Message

根据 OneBot 协议规定，消息是由不定数个消息段组成的 List。

以下列举支持的消息段：

## 文本消息 text

| 字段 | 类型   | 说明     |
| ---- | ------ | -------- |
| text | String | 消息文本 |

## 提及消息 mention

| 字段    | 类型   | 说明    |
| ------- | ------ | ------- |
| user_id | String | 用户 ID |

## 提及所有人消息 mention_all

无字段

## 表情消息 face

> *未支持发送该消息段*

| 字段 | 类型   | 说明     |
| ---- | ------ | -------- |
| id   | Int    | 表情 ID  |
| file | String | 表情名称 |

## 骰子消息 dice

> *未支持发送该消息段*

| 字段  | 类型 | 说明   |
| ----- | ---- | ------ |
| value | Int  | 骰子值 |

## 石头剪刀布消息 rps

> *未支持发送该消息段*

| 字段  | 类型 | 说明                          |
| ----- | ---- | ----------------------------- |
| value | Int  | 石头 => 0，剪刀 => 1，布 => 2 |

## 图片消息 image

| 字段    | 类型   | 说明        |
| ------- | ------ | ----------- |
| file_id | String | 图片文件 ID |
| url     | String | 图片 url    |

## 富文本消息 json

> *未支持发送该消息段*

| 字段 | 类型   | 说明      |
| ---- | ------ | --------- |
| data | String | json 内容 |

