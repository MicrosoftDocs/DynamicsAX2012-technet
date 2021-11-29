---
title: SalesOrdersController.GetInvoicesBySalesId Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetInvoicesBySalesId Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.SalesOrdersController.GetInvoicesBySalesId(System.Void)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.salesorderscontroller.getinvoicesbysalesid(v=AX.60)
ms:contentKeyID: 62203403
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.SalesOrdersController.GetInvoicesBySalesId
dev_langs:
- CSharp
- C++
- VB
---

# GetInvoicesBySalesId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.SalesInvoice)> _
Public Overridable Function GetInvoicesBySalesId ( _
    parameters As Void _
) As IReadOnlyCollection
'Usage
Dim instance As SalesOrdersController
Dim parameters As Void
Dim returnValue As IReadOnlyCollection

returnValue = instance.GetInvoicesBySalesId(parameters)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.SalesInvoice)]
public virtual IReadOnlyCollection GetInvoicesBySalesId(
    void parameters
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::SalesInvoice)]
public:
virtual IReadOnlyCollection^ GetInvoicesBySalesId(
    void parameters
)
```

#### Parameters

  - parameters  
    Type: [System.Void](https://technet.microsoft.com/library/skf099af\(v=ax.60\))  

#### Return Value

Type: IReadOnlyCollection  
Returns IReadOnlyCollection.  

## See Also

#### Reference

[SalesOrdersController Class](salesorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

