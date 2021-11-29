---
title: RetailDiscountLine.MixAndMatchLineNumberOfItemsNeeded Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MixAndMatchLineNumberOfItemsNeeded Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.MixAndMatchLineNumberOfItemsNeeded
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retaildiscountline.mixandmatchlinenumberofitemsneeded(v=AX.60)
ms:contentKeyID: 62204133
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine.MixAndMatchLineNumberOfItemsNeeded
dev_langs:
- CSharp
- C++
- VB
---

# MixAndMatchLineNumberOfItemsNeeded Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the number of items from the discount line group if this is a mix and match discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("NUMBEROFITEMSNEEDED")> _
Public Property MixAndMatchLineNumberOfItemsNeeded As Integer
    Get
    Set
'Usage
Dim instance As RetailDiscountLine
Dim value As Integer

value = instance.MixAndMatchLineNumberOfItemsNeeded

instance.MixAndMatchLineNumberOfItemsNeeded = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("NUMBEROFITEMSNEEDED")]
public int MixAndMatchLineNumberOfItemsNeeded { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"NUMBEROFITEMSNEEDED")]
public:
property int MixAndMatchLineNumberOfItemsNeeded {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[RetailDiscountLine Class](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

