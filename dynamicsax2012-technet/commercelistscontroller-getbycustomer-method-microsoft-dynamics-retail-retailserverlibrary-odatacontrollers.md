---
title: CommerceListsController.GetByCustomer Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetByCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceListsController.GetByCustomer(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.commercelistscontroller.getbycustomer(v=AX.60)
ms:contentKeyID: 62203200
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceListsController.GetByCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetByCustomer Method

Get all the commerce list filtered by customer ID.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.CustomerSearch)> _
Public Overridable Function GetByCustomer ( _
    parameters As ODataActionParameters _
) As IEnumerable(Of CommerceList)
'Usage
Dim instance As CommerceListsController
Dim parameters As ODataActionParameters
Dim returnValue As IEnumerable(Of CommerceList)

returnValue = instance.GetByCustomer(parameters)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.CustomerSearch)]
public virtual IEnumerable<CommerceList> GetByCustomer(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::CustomerSearch)]
public:
virtual IEnumerable<CommerceList^>^ GetByCustomer(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<CommerceList\>  
A collection of commerce list.  

## See Also

#### Reference

[CommerceListsController Class](commercelistscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

