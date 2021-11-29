---
title: IGlobalizationV1.SupportedCountryRegions Property  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: SupportedCountryRegions Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IGlobalizationV1.SupportedCountryRegions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iglobalizationv1.supportedcountryregions(v=AX.60)
ms:contentKeyID: 62205171
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IGlobalizationV1.SupportedCountryRegions
dev_langs:
- CSharp
- C++
- VB
---

# SupportedCountryRegions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the supported ISO country region codes.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property SupportedCountryRegions As ReadOnlyCollection(Of String)
    Get
'Usage
Dim instance As IGlobalizationV1
Dim value As ReadOnlyCollection(Of String)

value = instance.SupportedCountryRegions
```

``` csharp
ReadOnlyCollection<string> SupportedCountryRegions { get; }
```

``` c++
property ReadOnlyCollection<String^>^ SupportedCountryRegions {
    ReadOnlyCollection<String^>^ get ();
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[IGlobalizationV1 Interface](iglobalizationv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

