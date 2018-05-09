---
title: IPricingDataManagerV2.GetMixAndMatchLineGroupsByOfferIds Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetMixAndMatchLineGroupsByOfferIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.GetMixAndMatchLineGroupsByOfferIds(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanagerv2.getmixandmatchlinegroupsbyofferids(v=AX.60)
ms:contentKeyID: 62213786
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.GetMixAndMatchLineGroupsByOfferIds
dev_langs:
- CSharp
- C++
- VB
---

# GetMixAndMatchLineGroupsByOfferIds Method

Get all the mix and match line groups associated with the given offers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetMixAndMatchLineGroupsByOfferIds ( _
    offerIds As IEnumerable(Of String) _
) As ReadOnlyCollection(Of MixAndMatchLineGroup)
'Usage
Dim instance As IPricingDataManagerV2
Dim offerIds As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of MixAndMatchLineGroup)

returnValue = instance.GetMixAndMatchLineGroupsByOfferIds(offerIds)
```

``` csharp
ReadOnlyCollection<MixAndMatchLineGroup> GetMixAndMatchLineGroupsByOfferIds(
    IEnumerable<string> offerIds
)
```

``` c++
ReadOnlyCollection<MixAndMatchLineGroup^>^ GetMixAndMatchLineGroupsByOfferIds(
    IEnumerable<String^>^ offerIds
)
```

#### Parameters

  - offerIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[MixAndMatchLineGroup](mixandmatchlinegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Collection of mix and match line groups associated with the given offer Ids.  

## See Also

#### Reference

[IPricingDataManagerV2 Interface](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

