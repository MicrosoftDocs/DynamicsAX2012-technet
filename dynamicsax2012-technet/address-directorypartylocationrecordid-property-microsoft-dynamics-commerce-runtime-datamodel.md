---
title: Address.DirectoryPartyLocationRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DirectoryPartyLocationRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.DirectoryPartyLocationRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.directorypartylocationrecordid(v=AX.60)
ms:contentKeyID: 62203286
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.DirectoryPartyLocationRecordId
dev_langs:
- CSharp
- C++
- VB
---

# DirectoryPartyLocationRecordId Property

Gets or sets the directory party location record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ReadOnlyAttribute("DIRPARTYLOCATIONRECID")> _
<ColumnAttribute("DIRPARTYLOCATIONRECID")> _
<DataMemberAttribute> _
Public Property DirectoryPartyLocationRecordId As Long
    Get
    Set
'Usage
Dim instance As Address
Dim value As Long

value = instance.DirectoryPartyLocationRecordId

instance.DirectoryPartyLocationRecordId = value
```

``` csharp
[ReadOnlyAttribute("DIRPARTYLOCATIONRECID")]
[ColumnAttribute("DIRPARTYLOCATIONRECID")]
[DataMemberAttribute]
public long DirectoryPartyLocationRecordId { get; set; }
```

``` c++
[ReadOnlyAttribute(L"DIRPARTYLOCATIONRECID")]
[ColumnAttribute(L"DIRPARTYLOCATIONRECID")]
[DataMemberAttribute]
public:
property long long DirectoryPartyLocationRecordId {
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

