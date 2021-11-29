---
title: CartDeliveryPreferences.LineDeliveryPreferences Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDeliveryPreferences Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartDeliveryPreferences.LineDeliveryPreferences
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartdeliverypreferences.linedeliverypreferences(v=AX.60)
ms:contentKeyID: 65320828
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartDeliveryPreferences.LineDeliveryPreferences
dev_langs:
- CSharp
- C++
- VB
---

# LineDeliveryPreferences Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of delivery preferences that have been computed at line level.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineDeliveryPreferences As ReadOnlyCollection(Of LineDeliveryPreference)
    Get
    Private Set
'Usage
Dim instance As CartDeliveryPreferences
Dim value As ReadOnlyCollection(Of LineDeliveryPreference)

value = instance.LineDeliveryPreferences
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<LineDeliveryPreference> LineDeliveryPreferences { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<LineDeliveryPreference^>^ LineDeliveryPreferences {
    ReadOnlyCollection<LineDeliveryPreference^>^ get ();
    private: void set (ReadOnlyCollection<LineDeliveryPreference^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[LineDeliveryPreference](linedeliverypreference-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The line delivery preferences.  

## See Also

#### Reference

[CartDeliveryPreferences Class](cartdeliverypreferences-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

