---
title: ProductManager.GetProductDeliveryOptions Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetProductDeliveryOptions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetProductDeliveryOptions(Microsoft.Dynamics.Commerce.Runtime.DataModel.Address,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.getproductdeliveryoptions(v=AX.60)
ms:contentKeyID: 49850339
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetProductDeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# GetProductDeliveryOptions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the delivery options that are applicable to the given item and address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductDeliveryOptions ( _
    shippingAddress As Address, _
    itemId As String, _
    inventoryDimensionId As String _
) As ReadOnlyCollection(Of DeliveryOption)
'Usage
Dim instance As ProductManager
Dim shippingAddress As Address
Dim itemId As String
Dim inventoryDimensionId As String
Dim returnValue As ReadOnlyCollection(Of DeliveryOption)

returnValue = instance.GetProductDeliveryOptions(shippingAddress, _
    itemId, inventoryDimensionId)
```

``` csharp
public ReadOnlyCollection<DeliveryOption> GetProductDeliveryOptions(
    Address shippingAddress,
    string itemId,
    string inventoryDimensionId
)
```

``` c++
public:
ReadOnlyCollection<DeliveryOption^>^ GetProductDeliveryOptions(
    Address^ shippingAddress, 
    String^ itemId, 
    String^ inventoryDimensionId
)
```

#### Parameters

  - shippingAddress  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventoryDimensionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of delivery options.  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

