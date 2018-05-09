---
title: Customer.CreditRating Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CreditRating Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CreditRating
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customer.creditrating(v=AX.60)
ms:contentKeyID: 62213169
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CreditRating
dev_langs:
- CSharp
- C++
- VB
---

# CreditRating Property

Gets or sets the credit rating.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CREDITRATING")> _
Public Property CreditRating As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.CreditRating

instance.CreditRating = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CREDITRATING")]
public string CreditRating { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CREDITRATING")]
public:
property String^ CreditRating {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The credit rating.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

