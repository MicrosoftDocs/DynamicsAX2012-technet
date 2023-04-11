---
title: Customer.UsePurchaseRequest Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UsePurchaseRequest Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.UsePurchaseRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.usepurchaserequest(v=AX.60)
ms:contentKeyID: 62204346
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.UsePurchaseRequest
dev_langs:
- CSharp
- C++
- VB
---

# UsePurchaseRequest Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether UsePurchaseRequest is true or false.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("USEPURCHREQUEST")> _
<DataMemberAttribute> _
Public Property UsePurchaseRequest As Boolean
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Boolean

value = instance.UsePurchaseRequest

instance.UsePurchaseRequest = value
```

``` csharp
[ColumnAttribute("USEPURCHREQUEST")]
[DataMemberAttribute]
public bool UsePurchaseRequest { get; set; }
```

``` c++
[ColumnAttribute(L"USEPURCHREQUEST")]
[DataMemberAttribute]
public:
property bool UsePurchaseRequest {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

