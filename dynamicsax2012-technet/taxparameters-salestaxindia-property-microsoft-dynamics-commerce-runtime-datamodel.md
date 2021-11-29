---
title: TaxParameters.SalesTaxIndia Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesTaxIndia Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxParameters.SalesTaxIndia
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxparameters.salestaxindia(v=AX.60)
ms:contentKeyID: 62212751
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxParameters.SalesTaxIndia
dev_langs:
- CSharp
- C++
- VB
---

# SalesTaxIndia Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether sales tax parameter is enable.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESTAX_IN")> _
Public Property SalesTaxIndia As Boolean
    Get
    Set
'Usage
Dim instance As TaxParameters
Dim value As Boolean

value = instance.SalesTaxIndia

instance.SalesTaxIndia = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESTAX_IN")]
public bool SalesTaxIndia { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESTAX_IN")]
public:
property bool SalesTaxIndia {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value.  

## See Also

#### Reference

[TaxParameters Class](taxparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

