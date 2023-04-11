---
title: Customer.PersonNameId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PersonNameId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.PersonNameId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.personnameid(v=AX.60)
ms:contentKeyID: 62213583
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.PersonNameId
dev_langs:
- CSharp
- C++
- VB
---

# PersonNameId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the person name id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PERSONNAMEID")> _
Public Property PersonNameId As Long
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Long

value = instance.PersonNameId

instance.PersonNameId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PERSONNAMEID")]
public long PersonNameId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PERSONNAMEID")]
public:
property long long PersonNameId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The person name id.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

