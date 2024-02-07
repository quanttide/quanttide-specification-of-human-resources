# 职级序列

**职级序列(`RankCategory`)**是职级类别。

字段定义如下：

- **ID(`id`)**：系统定义的唯一标识符。
- **标识(`name`)**：用户自定义的标识字段，租户内唯一。
- **名称(`verboseName`)**：用户自定义的名称。

示例数据如下：

```json
{
    "id": 1,
    "name": "T",
    "verboseName": "技术序列"
}
```

## 职级序列关系

**职级序列(`RankCategoryRelation`)**是职级类别的所属关系。

字段定义如下：

- **ID(`id`)**：系统定义的唯一标识符。
- **创建时间(`createdAt`)**: 系统维护的创建时间。
- **父职级序列(`parent`)**: 上层职级序列。
- **子职级序列(`child`)**：下层职级序列。

示例数据如下：

```json
{
    "id": 1,
    "createdAt": "2024-02-05T08:00:00Z",
    "parent": {
        "id": 2,
        "name": "L",
        "verboseName": "一般职级序列"
    },
    "child": {
        "id": 1,
        "name": "T",
        "verboseName": "技术序列"
    }
}
```
