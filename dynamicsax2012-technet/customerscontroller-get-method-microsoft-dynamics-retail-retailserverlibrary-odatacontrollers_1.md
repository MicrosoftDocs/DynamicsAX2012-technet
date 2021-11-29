---
title: CustomersController.Get Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Get Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CustomersController.Get
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.customerscontroller.get(v=AX.60)
ms:contentKeyID: 62202918
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Get Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets Customers.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.CustomerSearch)> _
Public Overrides Function Get As IQueryable(Of Customer)
'Usage
Dim instance As CustomersController
Dim returnValue As IQueryable(Of Customer)

returnValue = instance.Get()
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.CustomerSearch)]
public override IQueryable<Customer> Get()
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::CustomerSearch)]
public:
virtual IQueryable<Customer^>^ Get() override
```

#### Return Value

Type: [System.Linq.IQueryable](https://technet.microsoft.com/library/bb351562\(v=ax.60\))\<Customer\>  
The [IQueryable](https://technet.microsoft.com/library/bb495796\(v=ax.60\)) of Customer.  

## See Also

#### Reference

[CustomersController Class](customerscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Get Overload](customerscontroller-get-method-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

