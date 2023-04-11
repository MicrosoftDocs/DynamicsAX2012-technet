---
title: SalesOrdersController.Search Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Search Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.SalesOrdersController.Search(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.salesorderscontroller.search(v=AX.60)
ms:contentKeyID: 62201859
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.SalesOrdersController.Search
dev_langs:
- CSharp
- C++
- VB
---

# Search Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Searchs for any orders matching the given search criteria.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function Search ( _
    parameters As ODataActionParameters _
) As IEnumerable(Of SalesOrder)
'Usage
Dim instance As SalesOrdersController
Dim parameters As ODataActionParameters
Dim returnValue As IEnumerable(Of SalesOrder)

returnValue = instance.Search(parameters)
```

``` csharp
[HttpPostAttribute]
public virtual IEnumerable<SalesOrder> Search(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
virtual IEnumerable<SalesOrder^>^ Search(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<SalesOrder\>  
The sales order object.  

## See Also

#### Reference

[SalesOrdersController Class](salesorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

