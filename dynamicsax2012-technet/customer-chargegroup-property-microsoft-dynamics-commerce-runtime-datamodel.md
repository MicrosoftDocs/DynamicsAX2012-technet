---
title: Customer.ChargeGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.ChargeGroup
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customer.chargegroup(v=AX.60)
ms:contentKeyID: 49847084
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.ChargeGroup
dev_langs:
- CSharp
- C++
- VB
---

# ChargeGroup Property

Gets or sets the customer's charge (markup) group for autocharges and shipping charges.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MARKUPGROUP")> _
<DataMemberAttribute> _
Public Property ChargeGroup As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.ChargeGroup

instance.ChargeGroup = value
```

``` csharp
[ColumnAttribute("MARKUPGROUP")]
[DataMemberAttribute]
public string ChargeGroup { get; set; }
```

``` c++
[ColumnAttribute(L"MARKUPGROUP")]
[DataMemberAttribute]
public:
property String^ ChargeGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The charge group.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

