---
title: TransferOrdersController.Get Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Get Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.TransferOrdersController.Get
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.transferorderscontroller.get(v=AX.60)
ms:contentKeyID: 62203100
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Get Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets open transfer orders for the store.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.PickingAndReceiving)> _
Public Overrides Function Get As IQueryable(Of TransferOrder)
'Usage
Dim instance As TransferOrdersController
Dim returnValue As IQueryable(Of TransferOrder)

returnValue = instance.Get()
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.PickingAndReceiving)]
public override IQueryable<TransferOrder> Get()
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::PickingAndReceiving)]
public:
virtual IQueryable<TransferOrder^>^ Get() override
```

#### Return Value

Type: [System.Linq.IQueryable](https://technet.microsoft.com/library/bb351562\(v=ax.60\))\<TransferOrder\>  
A collection of transfer orders.  

## See Also

#### Reference

[TransferOrdersController Class](transferorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Get Overload](transferorderscontroller-get-method-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

