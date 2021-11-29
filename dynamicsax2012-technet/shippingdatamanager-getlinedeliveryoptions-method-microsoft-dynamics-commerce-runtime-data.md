---
title: ShippingDataManager.GetLineDeliveryOptions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetLineDeliveryOptions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetLineDeliveryOptions(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.shippingdatamanager.getlinedeliveryoptions(v=AX.60)
ms:contentKeyID: 49840698
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetLineDeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# GetLineDeliveryOptions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the delivery options applicable for each sales line level.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetLineDeliveryOptions ( _
    salesLines As IEnumerable(Of SalesLine) _
) As ReadOnlyCollection(Of SalesLineDeliveryOption)
'Usage
Dim instance As ShippingDataManager
Dim salesLines As IEnumerable(Of SalesLine)
Dim returnValue As ReadOnlyCollection(Of SalesLineDeliveryOption)

returnValue = instance.GetLineDeliveryOptions(salesLines)
```

``` csharp
public ReadOnlyCollection<SalesLineDeliveryOption> GetLineDeliveryOptions(
    IEnumerable<SalesLine> salesLines
)
```

``` c++
public:
ReadOnlyCollection<SalesLineDeliveryOption^>^ GetLineDeliveryOptions(
    IEnumerable<SalesLine^>^ salesLines
)
```

#### Parameters

  - salesLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesLineDeliveryOption](saleslinedeliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The matching delivery options.  

## See Also

#### Reference

[ShippingDataManager Class](shippingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

