---
title: GetWarehouseDetailsResponse Constructor (IEnumerable(WarehouseDetails)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetWarehouseDetailsResponse Constructor (IEnumerable(WarehouseDetails))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetWarehouseDetailsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.WarehouseDetails})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getwarehousedetailsresponse.getwarehousedetailsresponse(v=AX.60)
ms:contentKeyID: 62208502
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetWarehouseDetailsResponse Constructor (IEnumerable(WarehouseDetails))

Initializes a new instance of the [GetWarehouseDetailsResponse](getwarehousedetailsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemDimensions As IEnumerable(Of WarehouseDetails) _
)
'Usage
Dim itemDimensions As IEnumerable(Of WarehouseDetails)

Dim instance As New GetWarehouseDetailsResponse(itemDimensions)
```

``` csharp
public GetWarehouseDetailsResponse(
    IEnumerable<WarehouseDetails> itemDimensions
)
```

``` c++
public:
GetWarehouseDetailsResponse(
    IEnumerable<WarehouseDetails^>^ itemDimensions
)
```

#### Parameters

  - itemDimensions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[WarehouseDetails](warehousedetails-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetWarehouseDetailsResponse Class](getwarehousedetailsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetWarehouseDetailsResponse Overload](getwarehousedetailsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

