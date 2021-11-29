---
title: Customer.UrlPartyLocationRecId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UrlPartyLocationRecId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.UrlPartyLocationRecId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.urlpartylocationrecid(v=AX.60)
ms:contentKeyID: 62211152
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.UrlPartyLocationRecId
dev_langs:
- CSharp
- C++
- VB
---

# UrlPartyLocationRecId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the URL party location rec id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("URLPARTYLOCATIONRECORDID")> _
Public Property UrlPartyLocationRecId As Long
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Long

value = instance.UrlPartyLocationRecId

instance.UrlPartyLocationRecId = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("URLPARTYLOCATIONRECORDID")]
public long UrlPartyLocationRecId { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"URLPARTYLOCATIONRECORDID")]
public:
property long long UrlPartyLocationRecId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The URL party location rec id.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

