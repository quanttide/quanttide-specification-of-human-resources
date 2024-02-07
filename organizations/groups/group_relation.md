# 员工组所属关系

**员工组所属关系(`EmployeeGroupRelation`)**是上下级员工组之间的所属关系。

字段定义如下：

- **ID(`id`)**：系统定义的唯一标识符。
- **创建时间(`createdAt`)**：系统维护的创建时间。
- **上级员工组(`parent`)**：用户创建的上级员工组。
- **下级员工组(`child`)**：用户创建的下级员工组。

示例数据如下：

```json
{
  "id": 1,
  "createdAt": "2024-02-05T08:00:00Z",
  "parent": {
    "id": 1,
    "name": "committee-of-managers",
    "verboseName": "负责人委员会"
  },
  "child": {
    "id": 2,
    "name": "committee-of-human-resources",
    "verboseName": "人力资源委员会"
  }
}
```
