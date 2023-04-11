---
title: TaxLine.TaxBasis Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxBasis Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLine.TaxBasis
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxline.taxbasis(v=AX.60)
ms:contentKeyID: 49835407
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLine.TaxBasis
dev_langs:
- CSharp
- C++
- VB
---

# TaxBasis Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax basis. A value used as starting point for tax formula.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TaxBasis As Decimal
    Get
    Set
'Usage
Dim instance As TaxLine
Dim value As Decimal

value = instance.TaxBasis

instance.TaxBasis = value
```

``` csharp
[DataMemberAttribute]
public decimal TaxBasis { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal TaxBasis {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TaxLine Class](taxline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

