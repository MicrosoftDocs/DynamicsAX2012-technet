---
title: GetLatestOfflineDatabaseChunksRequest.DatabaseType Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DatabaseType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetLatestOfflineDatabaseChunksRequest.DatabaseType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getlatestofflinedatabasechunksrequest.databasetype(v=AX.60)
ms:contentKeyID: 65320149
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetLatestOfflineDatabaseChunksRequest.DatabaseType
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseType Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DatabaseType As OfflineDatabaseType
    Get
    Set
'Usage
Dim instance As GetLatestOfflineDatabaseChunksRequest
Dim value As OfflineDatabaseType

value = instance.DatabaseType

instance.DatabaseType = value
```

``` csharp
[DataMemberAttribute]
public OfflineDatabaseType DatabaseType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property OfflineDatabaseType DatabaseType {
    OfflineDatabaseType get ();
    void set (OfflineDatabaseType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseType](offlinedatabasetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetLatestOfflineDatabaseChunksRequest Class](getlatestofflinedatabasechunksrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

