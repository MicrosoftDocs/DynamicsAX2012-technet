---
title: PeriodicDiscount.MixAndMatchLineNumberOfItemsNeeded Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MixAndMatchLineNumberOfItemsNeeded Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.MixAndMatchLineNumberOfItemsNeeded
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.mixandmatchlinenumberofitemsneeded(v=AX.60)
ms:contentKeyID: 49832782
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.MixAndMatchLineNumberOfItemsNeeded
dev_langs:
- CSharp
- C++
- VB
---

# MixAndMatchLineNumberOfItemsNeeded Property

Gets the number of items from the discount line group if this is a mix and match discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NUMBEROFITEMSNEEDED")> _
<DataMemberAttribute> _
Public Property MixAndMatchLineNumberOfItemsNeeded As Integer
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Integer

value = instance.MixAndMatchLineNumberOfItemsNeeded
```

``` csharp
[ColumnAttribute("NUMBEROFITEMSNEEDED")]
[DataMemberAttribute]
public int MixAndMatchLineNumberOfItemsNeeded { get; internal set; }
```

``` c++
[ColumnAttribute(L"NUMBEROFITEMSNEEDED")]
[DataMemberAttribute]
public:
property int MixAndMatchLineNumberOfItemsNeeded {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

