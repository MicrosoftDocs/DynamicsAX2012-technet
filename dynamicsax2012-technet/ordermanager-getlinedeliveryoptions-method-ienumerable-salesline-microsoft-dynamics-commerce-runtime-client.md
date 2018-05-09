---
title: OrderManager.GetLineDeliveryOptions Method (IEnumerable(SalesLine)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetLineDeliveryOptions Method (IEnumerable(SalesLine))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetLineDeliveryOptions(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getlinedeliveryoptions(v=AX.60)
ms:contentKeyID: 62214555
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetLineDeliveryOptions Method (IEnumerable(SalesLine))

Get the delivery options for each sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetLineDeliveryOptions ( _
    salesLines As IEnumerable(Of SalesLine) _
) As ReadOnlyCollection(Of SalesLineDeliveryOption)
'Usage
Dim instance As OrderManager
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
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[SalesLineDeliveryOption](saleslinedeliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The applicable delivery options at the line level.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetLineDeliveryOptions Overload](ordermanager-getlinedeliveryoptions-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

