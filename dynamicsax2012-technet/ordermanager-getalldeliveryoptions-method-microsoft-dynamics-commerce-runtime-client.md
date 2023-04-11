---
title: OrderManager.GetAllDeliveryOptions Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetAllDeliveryOptions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetAllDeliveryOptions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getalldeliveryoptions(v=AX.60)
ms:contentKeyID: 62207407
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetAllDeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# GetAllDeliveryOptions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets all available Delivery Options.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetAllDeliveryOptions As ReadOnlyCollection(Of DeliveryOption)
'Usage
Dim instance As OrderManager
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
All delivery options.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

