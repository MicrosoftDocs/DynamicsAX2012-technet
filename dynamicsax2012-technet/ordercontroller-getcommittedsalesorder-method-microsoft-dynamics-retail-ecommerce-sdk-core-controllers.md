---
title: OrderController.GetCommittedSalesOrder Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetCommittedSalesOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.OrderController.GetCommittedSalesOrder(System.String,System.Boolean,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.ordercontroller.getcommittedsalesorder(v=AX.60)
ms:contentKeyID: 65317713
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.OrderController.GetCommittedSalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetCommittedSalesOrder Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetCommittedSalesOrder ( _
    salesId As String, _
    includeSalesLines As Boolean, _
    searchEngine As ISearchEngine _
) As SalesOrder
'Usage
Dim instance As OrderController
Dim salesId As String
Dim includeSalesLines As Boolean
Dim searchEngine As ISearchEngine
Dim returnValue As SalesOrder

returnValue = instance.GetCommittedSalesOrder(salesId, _
    includeSalesLines, searchEngine)
```

``` csharp
public virtual SalesOrder GetCommittedSalesOrder(
    string salesId,
    bool includeSalesLines,
    ISearchEngine searchEngine
)
```

``` c++
public:
virtual SalesOrder^ GetCommittedSalesOrder(
    String^ salesId, 
    bool includeSalesLines, 
    ISearchEngine^ searchEngine
)
```

#### Parameters

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - includeSalesLines  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - searchEngine  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SalesOrder](salesorder-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[OrderController Class](ordercontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

