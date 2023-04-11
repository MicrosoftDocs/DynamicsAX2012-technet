---
title: Address.UrlRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UrlRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.UrlRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.urlrecordid(v=AX.60)
ms:contentKeyID: 62212895
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.UrlRecordId
dev_langs:
- CSharp
- C++
- VB
---

# UrlRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the URL record id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("URLRECORDID")> _
Public Property UrlRecordId As Long
    Get
    Set
'Usage
Dim instance As Address
Dim value As Long

value = instance.UrlRecordId

instance.UrlRecordId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("URLRECORDID")]
public long UrlRecordId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"URLRECORDID")]
public:
property long long UrlRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The URL record id.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

