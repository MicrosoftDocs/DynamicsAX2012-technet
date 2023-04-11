---
title: Address.DirectoryPartyLocationRoleRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DirectoryPartyLocationRoleRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.DirectoryPartyLocationRoleRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.directorypartylocationrolerecordid(v=AX.60)
ms:contentKeyID: 62214134
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.DirectoryPartyLocationRoleRecordId
dev_langs:
- CSharp
- C++
- VB
---

# DirectoryPartyLocationRoleRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the directory party location role record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DIRPARTYLOCATIONROLERECID")> _
<ReadOnlyAttribute("DIRPARTYLOCATIONROLERECID")> _
<DataMemberAttribute> _
Public Property DirectoryPartyLocationRoleRecordId As Long
    Get
    Set
'Usage
Dim instance As Address
Dim value As Long

value = instance.DirectoryPartyLocationRoleRecordId

instance.DirectoryPartyLocationRoleRecordId = value
```

``` csharp
[ColumnAttribute("DIRPARTYLOCATIONROLERECID")]
[ReadOnlyAttribute("DIRPARTYLOCATIONROLERECID")]
[DataMemberAttribute]
public long DirectoryPartyLocationRoleRecordId { get; set; }
```

``` c++
[ColumnAttribute(L"DIRPARTYLOCATIONROLERECID")]
[ReadOnlyAttribute(L"DIRPARTYLOCATIONROLERECID")]
[DataMemberAttribute]
public:
property long long DirectoryPartyLocationRoleRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The record identifier.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

