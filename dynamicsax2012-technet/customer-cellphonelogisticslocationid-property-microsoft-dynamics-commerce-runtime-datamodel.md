---
title: Customer.CellphoneLogisticsLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CellphoneLogisticsLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CellphoneLogisticsLocationId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customer.cellphonelogisticslocationid(v=AX.60)
ms:contentKeyID: 62206191
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CellphoneLogisticsLocationId
dev_langs:
- CSharp
- C++
- VB
---

# CellphoneLogisticsLocationId Property

Gets or sets the cellphone logistics location id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CELLPHONELOCATIONID")> _
Public Property CellphoneLogisticsLocationId As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.CellphoneLogisticsLocationId

instance.CellphoneLogisticsLocationId = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CELLPHONELOCATIONID")]
public string CellphoneLogisticsLocationId { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CELLPHONELOCATIONID")]
public:
property String^ CellphoneLogisticsLocationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The cellphone logistics location id.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

