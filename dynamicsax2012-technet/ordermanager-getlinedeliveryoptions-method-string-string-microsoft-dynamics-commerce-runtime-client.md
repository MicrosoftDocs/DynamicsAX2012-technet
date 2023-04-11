---
title: OrderManager.GetLineDeliveryOptions Method (String, String) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetLineDeliveryOptions Method (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetLineDeliveryOptions(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getlinedeliveryoptions(v=AX.60)
ms:contentKeyID: 49856554
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetLineDeliveryOptions Method (String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get the delivery options for each sales line in the cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetLineDeliveryOptions ( _
    cartId As String, _
    customerAccountNumber As String _
) As ReadOnlyCollection(Of SalesLineDeliveryOption)
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim customerAccountNumber As String
Dim returnValue As ReadOnlyCollection(Of SalesLineDeliveryOption)

returnValue = instance.GetLineDeliveryOptions(cartId, _
    customerAccountNumber)
```

``` csharp
public ReadOnlyCollection<SalesLineDeliveryOption> GetLineDeliveryOptions(
    string cartId,
    string customerAccountNumber
)
```

``` c++
public:
ReadOnlyCollection<SalesLineDeliveryOption^>^ GetLineDeliveryOptions(
    String^ cartId, 
    String^ customerAccountNumber
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesLineDeliveryOption](saleslinedeliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The applicable delivery options at the line level.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetLineDeliveryOptions Overload](ordermanager-getlinedeliveryoptions-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

