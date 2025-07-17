```
tip: 16
title: Account Multi-signature
author: Marcus Zhao(@zhaohong ) <zhaohong229@gmail.com> 
discussions to: https://github.com/tronprotocol/TIPs/issues/16
status: Final
type: Standards Track
category: TRC
created: 2018-12-27
```


AccountPermissionUpdateContract {
  owner_address: [TDtjEJJehNhxBXqzA3FTaussWL3CCoTfZY]
  owner: {
    type: Owner
    id: 0
    permission_name: "owner"
    threshold: 1
    parent_id: 0
    operations: "ffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff"
    keys: [
      {
        address: [TDtjEJJehNhxBXqzA3FTaussWL3CCoTfZY]
        weight: 1
      }
    ]
  }
  witness: {
    type: Witness
    id: 1
    permission_name: "witness"
    threshold: 1
    parent_id: 0
    operations: ""
    keys: [
      {
        address: [TDtjEJJehNhxBXqzA3FTaussWL3CCoTfZY]
        weight: 1
      }
    ]
  }
  actives: [
    {
      type: Active
      id: 2
      permission_name: "active"
      threshold: 1
      parent_id: 0
      operations: "ffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff"
      keys: [
        {
          address: [TDtjEJJehNhxBXqzA3FTaussWL3CCoTfZY]
          weight: 1
        }
      ]
    }
  ]
}
