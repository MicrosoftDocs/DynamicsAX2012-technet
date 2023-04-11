---
title: ProductDataManager.GetParentKitComponentInfo Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetParentKitComponentInfo Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.GetParentKitComponentInfo(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatamanager.getparentkitcomponentinfo(v=AX.60)
ms:contentKeyID: 65316256
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.GetParentKitComponentInfo
dev_langs:
- CSharp
- C++
- VB
---

# GetParentKitComponentInfo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetParentKitComponentInfo ( _
    kitComponentProductIds As IEnumerable(Of Long) _
) As ReadOnlyCollection(Of KitComponent)
'Usage
Dim instance As ProductDataManager
Dim kitComponentProductIds As IEnumerable(Of Long)
Dim returnValue As ReadOnlyCollection(Of KitComponent)

returnValue = instance.GetParentKitComponentInfo(kitComponentProductIds)
```

``` csharp
public ReadOnlyCollection<KitComponent> GetParentKitComponentInfo(
    IEnumerable<long> kitComponentProductIds
)
```

``` c++
public:
ReadOnlyCollection<KitComponent^>^ GetParentKitComponentInfo(
    IEnumerable<long long>^ kitComponentProductIds
)
```

#### Parameters

  - kitComponentProductIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[KitComponent](kitcomponent-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductDataManager Class](productdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

