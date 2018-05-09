---
title: SalesOrdersController.GetReceipts Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetReceipts Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.SalesOrdersController.GetReceipts(System.String,System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.salesorderscontroller.getreceipts(v=AX.60)
ms:contentKeyID: 62201985
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.SalesOrdersController.GetReceipts
dev_langs:
- CSharp
- C++
- VB
---

# GetReceipts Method

Gets a set of receipts based on the formTypes for Printing.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function GetReceipts ( _
    key As String, _
    parameters As ODataActionParameters _
) As IEnumerable(Of Receipt)
'Usage
Dim instance As SalesOrdersController
Dim key As String
Dim parameters As ODataActionParameters
Dim returnValue As IEnumerable(Of Receipt)

returnValue = instance.GetReceipts(key, _
    parameters)
```

``` csharp
[HttpPostAttribute]
public virtual IEnumerable<Receipt> GetReceipts(
    string key,
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
virtual IEnumerable<Receipt^>^ GetReceipts(
    String^ key, 
    ODataActionParameters^ parameters
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<Receipt\>  
The receipt object.  

## See Also

#### Reference

[SalesOrdersController Class](salesorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

