---
title: Customer.EmailPartyLocationRecId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmailPartyLocationRecId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.EmailPartyLocationRecId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.emailpartylocationrecid(v=AX.60)
ms:contentKeyID: 62208055
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.EmailPartyLocationRecId
dev_langs:
- CSharp
- C++
- VB
---

# EmailPartyLocationRecId Property

Gets or sets the email party location rec id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EMAILPARTYLOCATIONRECORDID")> _
<IgnoreDataMemberAttribute> _
Public Property EmailPartyLocationRecId As Long
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Long

value = instance.EmailPartyLocationRecId

instance.EmailPartyLocationRecId = value
```

``` csharp
[ColumnAttribute("EMAILPARTYLOCATIONRECORDID")]
[IgnoreDataMemberAttribute]
public long EmailPartyLocationRecId { get; set; }
```

``` c++
[ColumnAttribute(L"EMAILPARTYLOCATIONRECORDID")]
[IgnoreDataMemberAttribute]
public:
property long long EmailPartyLocationRecId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The email party location rec id.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

