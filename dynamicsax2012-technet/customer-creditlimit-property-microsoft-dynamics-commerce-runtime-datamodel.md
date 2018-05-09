---
title: Customer.CreditLimit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CreditLimit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CreditLimit
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customer.creditlimit(v=AX.60)
ms:contentKeyID: 62205739
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CreditLimit
dev_langs:
- CSharp
- C++
- VB
---

# CreditLimit Property

Gets or sets the credit limit.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CREDITMAX")> _
<DataMemberAttribute> _
Public Property CreditLimit As Decimal
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Decimal

value = instance.CreditLimit

instance.CreditLimit = value
```

``` csharp
[ColumnAttribute("CREDITMAX")]
[DataMemberAttribute]
public decimal CreditLimit { get; set; }
```

``` c++
[ColumnAttribute(L"CREDITMAX")]
[DataMemberAttribute]
public:
property Decimal CreditLimit {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The credit limit.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

