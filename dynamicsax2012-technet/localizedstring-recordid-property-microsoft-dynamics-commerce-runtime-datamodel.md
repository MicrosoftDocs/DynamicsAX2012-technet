---
title: LocalizedString.RecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LocalizedString.RecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.localizedstring.recordid(v=AX.60)
ms:contentKeyID: 62212693
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LocalizedString.RecordId
dev_langs:
- CSharp
- C++
- VB
---

# RecordId Property

Gets or sets the record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RECID")> _
<KeyAttribute> _
<DataMemberAttribute> _
Public Property RecordId As Long
    Get
    Set
'Usage
Dim instance As LocalizedString
Dim value As Long

value = instance.RecordId

instance.RecordId = value
```

``` csharp
[ColumnAttribute("RECID")]
[KeyAttribute]
[DataMemberAttribute]
public long RecordId { get; set; }
```

``` c++
[ColumnAttribute(L"RECID")]
[KeyAttribute]
[DataMemberAttribute]
public:
property long long RecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[LocalizedString Class](localizedstring-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

