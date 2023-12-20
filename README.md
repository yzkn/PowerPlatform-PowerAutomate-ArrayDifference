# PowerPlatform-PowerAutomate-ArrayDifference

Power Automate クラウドフローで配列の差分チェックを行い、追加／削除する要素を列挙する

---

- Before

```json
[
    {
        "Key": "Key001",
        "Value": "Value001"
    },
    {
        "Key": "Key002",
        "Value": "Value002"
    },
    {
        "Key": "Key003",
        "Value": "Value003"
    },
    {
        "Key": "Key004",
        "Value": "Value004"
    },
    {
        "Key": "Key005",
        "Value": "Value005"
    }
]
```

- After

```json
[
    {
        "Key": "Key001",
        "Value": "Value001"
    },
    {
        "Key": "Key002",
        "Value": "Value002"
    },
    {
        "Key": "Key003",
        "Value": "Value003"
    },
    {
        "Key": "Key004",
        "Value": "Value104"
    },
    {
        "Key": "Key006",
        "Value": "Value006"
    },
]
```

---

Copyright (c) 2023 YA-androidapp(https://github.com/yzkn) All rights reserved.
