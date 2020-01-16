---
title: OrderManager.GetOrderDeliveryOptions Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOrderDeliveryOptions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetOrderDeliveryOptions(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getorderdeliveryoptions(v=AX.60)
ms:contentKeyID: 49841950
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetOrderDeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# GetOrderDeliveryOptions Method

Get the Delivery options for the entire order i.e., the delivery options that are common to all the lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOrderDeliveryOptions ( _
    cartId As String, _
    customerAccountNumber As String _
) As ReadOnlyCollection(Of DeliveryOption)
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim customerAccountNumber As String
Dim returnValue As ReadOnlyCollection(Of DeliveryOption)

returnValue = instance.GetOrderDeliveryOptions(cartId, _
    customerAccountNumber)
```

``` csharp
public ReadOnlyCollection<DeliveryOption> GetOrderDeliveryOptions(
    string cartId,
    string customerAccountNumber
)
```

``` c++
public:
ReadOnlyCollection<DeliveryOption^>^ GetOrderDeliveryOptions(
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

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The applicable delivery options at the order level.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

