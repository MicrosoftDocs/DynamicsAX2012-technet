---
title: Shift.StoreRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StoreRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.StoreRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.storerecordid(v=AX.60)
ms:contentKeyID: 62214696
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.StoreRecordId
dev_langs:
- CSharp
- C++
- VB
---

# StoreRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets Store Record identifier of shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CHANNEL")> _
<DataMemberAttribute> _
Public Property StoreRecordId As Long
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Long

value = instance.StoreRecordId

instance.StoreRecordId = value
```

``` csharp
[ColumnAttribute("CHANNEL")]
[DataMemberAttribute]
public long StoreRecordId { get; set; }
```

``` c++
[ColumnAttribute(L"CHANNEL")]
[DataMemberAttribute]
public:
property long long StoreRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

