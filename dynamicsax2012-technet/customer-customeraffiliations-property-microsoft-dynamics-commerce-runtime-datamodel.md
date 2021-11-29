---
title: Customer.CustomerAffiliations Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerAffiliations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CustomerAffiliations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.customeraffiliations(v=AX.60)
ms:contentKeyID: 62209220
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CustomerAffiliations
dev_langs:
- CSharp
- C++
- VB
---

# CustomerAffiliations Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer affiliations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerAffiliations As IList(Of CustomerAffiliation)
    Get
    Set
'Usage
Dim instance As Customer
Dim value As IList(Of CustomerAffiliation)

value = instance.CustomerAffiliations

instance.CustomerAffiliations = value
```

``` csharp
[DataMemberAttribute]
public IList<CustomerAffiliation> CustomerAffiliations { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<CustomerAffiliation^>^ CustomerAffiliations {
    IList<CustomerAffiliation^>^ get ();
    void set (IList<CustomerAffiliation^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[CustomerAffiliation](customeraffiliation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

