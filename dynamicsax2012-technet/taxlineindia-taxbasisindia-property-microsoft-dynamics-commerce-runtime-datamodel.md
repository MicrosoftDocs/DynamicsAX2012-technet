---
title: TaxLineIndia.TaxBasisIndia Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxBasisIndia Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TaxBasisIndia
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxlineindia.taxbasisindia(v=AX.60)
ms:contentKeyID: 62211328
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TaxBasisIndia
dev_langs:
- CSharp
- C++
- VB
---

# TaxBasisIndia Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets tax basis.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXBASIS")> _
Public Property TaxBasisIndia As Decimal
    Get
    Set
'Usage
Dim instance As TaxLineIndia
Dim value As Decimal

value = instance.TaxBasisIndia

instance.TaxBasisIndia = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXBASIS")]
public decimal TaxBasisIndia { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXBASIS")]
public:
property Decimal TaxBasisIndia {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TaxLineIndia Class](taxlineindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

