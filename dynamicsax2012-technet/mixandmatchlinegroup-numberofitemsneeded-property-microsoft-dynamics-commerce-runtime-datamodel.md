---
title: MixAndMatchLineGroup.NumberOfItemsNeeded Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NumberOfItemsNeeded Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.MixAndMatchLineGroup.NumberOfItemsNeeded
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.mixandmatchlinegroup.numberofitemsneeded(v=AX.60)
ms:contentKeyID: 49834846
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.MixAndMatchLineGroup.NumberOfItemsNeeded
dev_langs:
- CSharp
- C++
- VB
---

# NumberOfItemsNeeded Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the number of items needed for a mix and match group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NUMBEROFITEMSNEEDED")> _
<DataMemberAttribute> _
Public Property NumberOfItemsNeeded As Integer
    Get
    Friend Set
'Usage
Dim instance As MixAndMatchLineGroup
Dim value As Integer

value = instance.NumberOfItemsNeeded
```

``` csharp
[ColumnAttribute("NUMBEROFITEMSNEEDED")]
[DataMemberAttribute]
public int NumberOfItemsNeeded { get; internal set; }
```

``` c++
[ColumnAttribute(L"NUMBEROFITEMSNEEDED")]
[DataMemberAttribute]
public:
property int NumberOfItemsNeeded {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[MixAndMatchLineGroup Class](mixandmatchlinegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

