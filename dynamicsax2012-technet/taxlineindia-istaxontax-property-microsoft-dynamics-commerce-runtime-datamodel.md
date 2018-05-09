---
title: TaxLineIndia.IsTaxOnTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsTaxOnTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.IsTaxOnTax
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxlineindia.istaxontax(v=AX.60)
ms:contentKeyID: 62211065
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.IsTaxOnTax
dev_langs:
- CSharp
- C++
- VB
---

# IsTaxOnTax Property

Gets or sets a value indicating whether the tax item is an India tax on tax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISTAXONTAX")> _
Public Property IsTaxOnTax As Boolean
    Get
    Set
'Usage
Dim instance As TaxLineIndia
Dim value As Boolean

value = instance.IsTaxOnTax

instance.IsTaxOnTax = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISTAXONTAX")]
public bool IsTaxOnTax { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISTAXONTAX")]
public:
property bool IsTaxOnTax {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[TaxLineIndia Class](taxlineindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

