---
title: Customer.PhonePartyLocationRecId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PhonePartyLocationRecId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.PhonePartyLocationRecId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.phonepartylocationrecid(v=AX.60)
ms:contentKeyID: 62210757
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.PhonePartyLocationRecId
dev_langs:
- CSharp
- C++
- VB
---

# PhonePartyLocationRecId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the phone party location rec id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("PHONEPARTYLOCATIONRECORDID")> _
Public Property PhonePartyLocationRecId As Long
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Long

value = instance.PhonePartyLocationRecId

instance.PhonePartyLocationRecId = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("PHONEPARTYLOCATIONRECORDID")]
public long PhonePartyLocationRecId { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"PHONEPARTYLOCATIONRECORDID")]
public:
property long long PhonePartyLocationRecId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The phone party location rec id.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

