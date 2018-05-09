---
title: OrderManager.GetOrdersByCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOrdersByCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetOrdersByCustomer(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getordersbycustomer(v=AX.60)
ms:contentKeyID: 65321461
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetOrdersByCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetOrdersByCustomer Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOrdersByCustomer ( _
    settings As QueryResultSettings, _
    customerAccountNumber As String _
) As ReadOnlyCollection(Of SalesOrder)
'Usage
Dim instance As OrderManager
Dim settings As QueryResultSettings
Dim customerAccountNumber As String
Dim returnValue As ReadOnlyCollection(Of SalesOrder)

returnValue = instance.GetOrdersByCustomer(settings, _
    customerAccountNumber)
```

``` csharp
public ReadOnlyCollection<SalesOrder> GetOrdersByCustomer(
    QueryResultSettings settings,
    string customerAccountNumber
)
```

``` c++
public:
ReadOnlyCollection<SalesOrder^>^ GetOrdersByCustomer(
    QueryResultSettings^ settings, 
    String^ customerAccountNumber
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

