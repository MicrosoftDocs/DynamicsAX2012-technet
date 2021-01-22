---
title: Customer.NonChargeableAccount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NonChargeableAccount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.NonChargeableAccount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.nonchargeableaccount(v=AX.60)
ms:contentKeyID: 62209707
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.NonChargeableAccount
dev_langs:
- CSharp
- C++
- VB
---

# NonChargeableAccount Property

Gets or sets a value indicating whether the customer is non-chargeable account.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NONCHARGEABLEACCOUNT")> _
<DataMemberAttribute> _
Public Property NonChargeableAccount As Boolean
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Boolean

value = instance.NonChargeableAccount

instance.NonChargeableAccount = value
```

``` csharp
[ColumnAttribute("NONCHARGEABLEACCOUNT")]
[DataMemberAttribute]
public bool NonChargeableAccount { get; set; }
```

``` c++
[ColumnAttribute(L"NONCHARGEABLEACCOUNT")]
[DataMemberAttribute]
public:
property bool NonChargeableAccount {
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

