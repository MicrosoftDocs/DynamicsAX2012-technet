---
title: Customer.DirectoryPartyRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DirectoryPartyRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.DirectoryPartyRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.directorypartyrecordid(v=AX.60)
ms:contentKeyID: 62214412
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.DirectoryPartyRecordId
dev_langs:
- CSharp
- C++
- VB
---

# DirectoryPartyRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the record identifier for the DirPartyTable.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PARTY")> _
Public Property DirectoryPartyRecordId As Long
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Long

value = instance.DirectoryPartyRecordId

instance.DirectoryPartyRecordId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PARTY")]
public long DirectoryPartyRecordId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PARTY")]
public:
property long long DirectoryPartyRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

