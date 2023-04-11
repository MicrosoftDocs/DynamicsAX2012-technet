---
title: SalesTransaction.CustomerOrderType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerOrderType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.CustomerOrderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.customerordertype(v=AX.60)
ms:contentKeyID: 62208990
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.CustomerOrderType
dev_langs:
- CSharp
- C++
- VB
---

# CustomerOrderType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer order type representing the order type in the headquarters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CUSTOMERORDERTYPE")> _
Public Property CustomerOrderType As CustomerOrderType
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As CustomerOrderType

value = instance.CustomerOrderType

instance.CustomerOrderType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CUSTOMERORDERTYPE")]
public CustomerOrderType CustomerOrderType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CUSTOMERORDERTYPE")]
public:
property CustomerOrderType CustomerOrderType {
    CustomerOrderType get ();
    void set (CustomerOrderType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderType](customerordertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CustomerOrderType](customerordertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

