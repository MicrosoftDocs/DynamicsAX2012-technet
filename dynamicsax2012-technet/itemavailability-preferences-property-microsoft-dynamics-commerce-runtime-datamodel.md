---
title: ItemAvailability.Preferences Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Preferences Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability.Preferences
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailability.preferences(v=AX.60)
ms:contentKeyID: 49831759
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability.Preferences
dev_langs:
- CSharp
- C++
- VB
---

# Preferences Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the preferences.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PREFERENCES")> _
<IgnoreDataMemberAttribute> _
Public Property Preferences As ItemAvailabilityPreferences
    Get
    Friend Set
'Usage
Dim instance As ItemAvailability
Dim value As ItemAvailabilityPreferences

value = instance.Preferences
```

``` csharp
[ColumnAttribute("PREFERENCES")]
[IgnoreDataMemberAttribute]
public ItemAvailabilityPreferences Preferences { get; internal set; }
```

``` c++
[ColumnAttribute(L"PREFERENCES")]
[IgnoreDataMemberAttribute]
public:
property ItemAvailabilityPreferences Preferences {
    ItemAvailabilityPreferences get ();
    internal: void set (ItemAvailabilityPreferences value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilityPreferences](itemavailabilitypreferences-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ItemAvailabilityPreferences](itemavailabilitypreferences-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ItemAvailability Class](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

