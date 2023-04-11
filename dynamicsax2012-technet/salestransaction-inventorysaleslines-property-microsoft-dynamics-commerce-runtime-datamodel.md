---
title: SalesTransaction.InventorySalesLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventorySalesLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.InventorySalesLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.inventorysaleslines(v=AX.60)
ms:contentKeyID: 62202286
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.InventorySalesLines
dev_langs:
- CSharp
- C++
- VB
---

# InventorySalesLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales lines that needs to be included in the calculations other than totaling and tax. The collection excludes voided lines and return-by-receipt lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property InventorySalesLines As ReadOnlyCollection(Of SalesLine)
    Get
'Usage
Dim instance As SalesTransaction
Dim value As ReadOnlyCollection(Of SalesLine)

value = instance.InventorySalesLines
```

``` csharp
[IgnoreDataMemberAttribute]
public ReadOnlyCollection<SalesLine> InventorySalesLines { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ReadOnlyCollection<SalesLine^>^ InventorySalesLines {
    ReadOnlyCollection<SalesLine^>^ get ();
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The inventory sales lines.  

## Remarks

Please refrain from using this property. Use or instead.

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

