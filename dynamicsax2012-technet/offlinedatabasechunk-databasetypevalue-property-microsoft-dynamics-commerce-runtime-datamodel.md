---
title: OfflineDatabaseChunk.DatabaseTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DatabaseTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk.DatabaseTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.offlinedatabasechunk.databasetypevalue(v=AX.60)
ms:contentKeyID: 65323021
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineDatabaseChunk.DatabaseTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the database type identifier value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DatabaseTypeValue As Integer
    Get
    Set
'Usage
Dim instance As OfflineDatabaseChunk
Dim value As Integer

value = instance.DatabaseTypeValue

instance.DatabaseTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int DatabaseTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int DatabaseTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## Remarks

Used by Web API.

## See Also

#### Reference

[OfflineDatabaseChunk Class](offlinedatabasechunk-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

