---
title: OrderController.GetSalesOrdersByCustomer Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetSalesOrdersByCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.OrderController.GetSalesOrdersByCustomer(System.String,System.Boolean,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.ordercontroller.getsalesordersbycustomer(v=AX.60)
ms:contentKeyID: 65317464
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.OrderController.GetSalesOrdersByCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesOrdersByCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetSalesOrdersByCustomer ( _
    accountNumber As String, _
    includeSalesLines As Boolean, _
    searchEngine As ISearchEngine _
) As IEnumerable(Of SalesOrder)
'Usage
Dim instance As OrderController
Dim accountNumber As String
Dim includeSalesLines As Boolean
Dim searchEngine As ISearchEngine
Dim returnValue As IEnumerable(Of SalesOrder)

returnValue = instance.GetSalesOrdersByCustomer(accountNumber, _
    includeSalesLines, searchEngine)
```

``` csharp
public virtual IEnumerable<SalesOrder> GetSalesOrdersByCustomer(
    string accountNumber,
    bool includeSalesLines,
    ISearchEngine searchEngine
)
```

``` c++
public:
virtual IEnumerable<SalesOrder^>^ GetSalesOrdersByCustomer(
    String^ accountNumber, 
    bool includeSalesLines, 
    ISearchEngine^ searchEngine
)
```

#### Parameters

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - includeSalesLines  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - searchEngine  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesOrder](salesorder-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[OrderController Class](ordercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

