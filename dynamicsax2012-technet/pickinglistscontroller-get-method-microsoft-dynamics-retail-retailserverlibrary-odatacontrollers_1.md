---
title: PickingListsController.Get Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Get Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PickingListsController.Get
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.pickinglistscontroller.get(v=AX.60)
ms:contentKeyID: 62202170
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

Gets picking lists as IQueryable for the store.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.PickingAndReceiving)> _
Public Overrides Function Get As IQueryable(Of PickingList)
'Usage
Dim instance As PickingListsController
Dim returnValue As IQueryable(Of PickingList)

returnValue = instance.Get()
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.PickingAndReceiving)]
public override IQueryable<PickingList> Get()
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::PickingAndReceiving)]
public:
virtual IQueryable<PickingList^>^ Get() override
```

#### Return Value

Type: [System.Linq.IQueryable](https://technet.microsoft.com/library/bb351562\(v=ax.60\))\<PickingList\>  
A collection of picking lists.  

## See Also

#### Reference

[PickingListsController Class](pickinglistscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Get Overload](pickinglistscontroller-get-method-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

