---
title: Address.ExpireRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExpireRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.ExpireRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.expirerecordid(v=AX.60)
ms:contentKeyID: 62210221
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.ExpireRecordId
dev_langs:
- CSharp
- C++
- VB
---

# ExpireRecordId Property

Gets or sets the expire record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ReadOnlyAttribute("EXPIRERECORDID")> _
<ColumnAttribute("EXPIRERECORDID")> _
<DataMemberAttribute> _
Public Property ExpireRecordId As Long
    Get
    Set
'Usage
Dim instance As Address
Dim value As Long

value = instance.ExpireRecordId

instance.ExpireRecordId = value
```

``` csharp
[ReadOnlyAttribute("EXPIRERECORDID")]
[ColumnAttribute("EXPIRERECORDID")]
[DataMemberAttribute]
public long ExpireRecordId { get; set; }
```

``` c++
[ReadOnlyAttribute(L"EXPIRERECORDID")]
[ColumnAttribute(L"EXPIRERECORDID")]
[DataMemberAttribute]
public:
property long long ExpireRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The expire record identifier.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

