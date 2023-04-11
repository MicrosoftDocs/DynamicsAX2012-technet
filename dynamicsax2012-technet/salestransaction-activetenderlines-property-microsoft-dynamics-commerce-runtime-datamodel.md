---
title: SalesTransaction.ActiveTenderLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ActiveTenderLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ActiveTenderLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.activetenderlines(v=AX.60)
ms:contentKeyID: 62204957
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ActiveTenderLines
dev_langs:
- CSharp
- C++
- VB
---

# ActiveTenderLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the active (not voided and not historical) tender lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property ActiveTenderLines As ReadOnlyCollection(Of TenderLine)
    Get
'Usage
Dim instance As SalesTransaction
Dim value As ReadOnlyCollection(Of TenderLine)

value = instance.ActiveTenderLines
```

``` csharp
[IgnoreDataMemberAttribute]
public ReadOnlyCollection<TenderLine> ActiveTenderLines { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ReadOnlyCollection<TenderLine^>^ ActiveTenderLines {
    ReadOnlyCollection<TenderLine^>^ get ();
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

