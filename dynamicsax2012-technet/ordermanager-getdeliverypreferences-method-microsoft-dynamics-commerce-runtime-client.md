---
title: OrderManager.GetDeliveryPreferences Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetDeliveryPreferences Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetDeliveryPreferences(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getdeliverypreferences(v=AX.60)
ms:contentKeyID: 65318211
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetDeliveryPreferences
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryPreferences Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetDeliveryPreferences ( _
    cartId As String _
) As CartDeliveryPreferences
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim returnValue As CartDeliveryPreferences

returnValue = instance.GetDeliveryPreferences(cartId)
```

``` csharp
public CartDeliveryPreferences GetDeliveryPreferences(
    string cartId
)
```

``` c++
public:
CartDeliveryPreferences^ GetDeliveryPreferences(
    String^ cartId
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartDeliveryPreferences](cartdeliverypreferences-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

