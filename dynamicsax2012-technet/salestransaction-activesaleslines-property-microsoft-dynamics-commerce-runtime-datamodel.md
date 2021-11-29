---
title: SalesTransaction.ActiveSalesLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ActiveSalesLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ActiveSalesLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.activesaleslines(v=AX.60)
ms:contentKeyID: 62212273
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ActiveSalesLines
dev_langs:
- CSharp
- C++
- VB
---

# ActiveSalesLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the active (not voided) sales lines. Totaling and tax should include all the active lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property ActiveSalesLines As ReadOnlyCollection(Of SalesLine)
    Get
'Usage
Dim instance As SalesTransaction
Dim value As ReadOnlyCollection(Of SalesLine)

value = instance.ActiveSalesLines
```

``` csharp
[IgnoreDataMemberAttribute]
public ReadOnlyCollection<SalesLine> ActiveSalesLines { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ReadOnlyCollection<SalesLine^>^ ActiveSalesLines {
    ReadOnlyCollection<SalesLine^>^ get ();
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## Remarks

Need to recalculate tax on return-by-receipt lines, because we cannot reconstruct tax lines from return transaction lines alone. Some key information like IsExempt, IsTaxInclusive, TaxCode are not available on return transaction line.

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

