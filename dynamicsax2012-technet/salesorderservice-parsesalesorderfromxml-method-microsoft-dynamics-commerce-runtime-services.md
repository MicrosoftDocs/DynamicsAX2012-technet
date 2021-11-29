---
title: SalesOrderService.ParseSalesOrderFromXml Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: ParseSalesOrderFromXml Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService.ParseSalesOrderFromXml(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.salesorderservice.parsesalesorderfromxml(v=AX.60)
ms:contentKeyID: 49820243
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.SalesOrderService.ParseSalesOrderFromXml
dev_langs:
- CSharp
- C++
- VB
---

# ParseSalesOrderFromXml Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Parse a Sales Order from XML.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function ParseSalesOrderFromXml ( _
    xml As String _
) As SalesOrder
'Usage
Dim xml As String
Dim returnValue As SalesOrder

returnValue = SalesOrderService.ParseSalesOrderFromXml(xml)
```

``` csharp
protected static SalesOrder ParseSalesOrderFromXml(
    string xml
)
```

``` c++
protected:
static SalesOrder^ ParseSalesOrderFromXml(
    String^ xml
)
```

#### Parameters

  - xml  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Sales Order object if successfull, null otherwise.  

## See Also

#### Reference

[SalesOrderService Class](salesorderservice-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

