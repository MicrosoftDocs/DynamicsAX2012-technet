---
title: ContactInfo.PartyLocationRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PartyLocationRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.PartyLocationRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.contactinfo.partylocationrecordid(v=AX.60)
ms:contentKeyID: 62207819
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.PartyLocationRecordId
dev_langs:
- CSharp
- C++
- VB
---

# PartyLocationRecordId Property

Gets or sets the party location record id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DIRPARTYLOCATIONRECORDID")> _
<DataMemberAttribute> _
Public Property PartyLocationRecordId As Long
    Get
    Set
'Usage
Dim instance As ContactInfo
Dim value As Long

value = instance.PartyLocationRecordId

instance.PartyLocationRecordId = value
```

``` csharp
[ColumnAttribute("DIRPARTYLOCATIONRECORDID")]
[DataMemberAttribute]
public long PartyLocationRecordId { get; set; }
```

``` c++
[ColumnAttribute(L"DIRPARTYLOCATIONRECORDID")]
[DataMemberAttribute]
public:
property long long PartyLocationRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The party location record id.  

## See Also

#### Reference

[ContactInfo Class](contactinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

