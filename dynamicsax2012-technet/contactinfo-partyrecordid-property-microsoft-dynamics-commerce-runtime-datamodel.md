---
title: ContactInfo.PartyRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PartyRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.PartyRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.contactinfo.partyrecordid(v=AX.60)
ms:contentKeyID: 62209567
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.PartyRecordId
dev_langs:
- CSharp
- C++
- VB
---

# PartyRecordId Property

Gets or sets the party record id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DIRPARTYRECORDID")> _
<DataMemberAttribute> _
Public Property PartyRecordId As Long
    Get
    Set
'Usage
Dim instance As ContactInfo
Dim value As Long

value = instance.PartyRecordId

instance.PartyRecordId = value
```

``` csharp
[ColumnAttribute("DIRPARTYRECORDID")]
[DataMemberAttribute]
public long PartyRecordId { get; set; }
```

``` c++
[ColumnAttribute(L"DIRPARTYRECORDID")]
[DataMemberAttribute]
public:
property long long PartyRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The party record id.  

## See Also

#### Reference

[ContactInfo Class](contactinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

