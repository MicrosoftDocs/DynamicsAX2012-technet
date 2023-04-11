---
title: ShippingDataManager.GetAllDeliveryOptions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetAllDeliveryOptions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetAllDeliveryOptions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.shippingdatamanager.getalldeliveryoptions(v=AX.60)
ms:contentKeyID: 62210821
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShippingDataManager.GetAllDeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# GetAllDeliveryOptions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets all delivery options available for the channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetAllDeliveryOptions As ReadOnlyCollection(Of DeliveryOption)
'Usage
Dim instance As ShippingDataManager
Dim returnValue As ReadOnlyCollection(Of DeliveryOption)

returnValue = instance.GetAllDeliveryOptions()
```

``` csharp
public ReadOnlyCollection<DeliveryOption> GetAllDeliveryOptions()
```

``` c++
public:
ReadOnlyCollection<DeliveryOption^>^ GetAllDeliveryOptions()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Delivery options available for the channel.  

## See Also

#### Reference

[ShippingDataManager Class](shippingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

