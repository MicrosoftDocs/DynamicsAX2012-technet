---
title: SalesOrdersController.GetByReceiptId Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetByReceiptId Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.SalesOrdersController.GetByReceiptId(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.salesorderscontroller.getbyreceiptid(v=AX.60)
ms:contentKeyID: 62202513
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.SalesOrdersController.GetByReceiptId
dev_langs:
- CSharp
- C++
- VB
---

# GetByReceiptId Method

Gets the sales order by the receipt identifier.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function GetByReceiptId ( _
    parameters As ODataActionParameters _
) As IEnumerable(Of SalesOrder)
'Usage
Dim instance As SalesOrdersController
Dim parameters As ODataActionParameters
Dim returnValue As IEnumerable(Of SalesOrder)

returnValue = instance.GetByReceiptId(parameters)
```

``` csharp
[HttpPostAttribute]
public virtual IEnumerable<SalesOrder> GetByReceiptId(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
virtual IEnumerable<SalesOrder^>^ GetByReceiptId(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<SalesOrder\>  
The found sales orders.  

## See Also

#### Reference

[SalesOrdersController Class](salesorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

