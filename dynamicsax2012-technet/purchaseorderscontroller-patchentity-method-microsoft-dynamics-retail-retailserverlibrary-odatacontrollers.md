---
title: PurchaseOrdersController.PatchEntity Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: PatchEntity Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PurchaseOrdersController.PatchEntity(System.String,System.Web.Http.OData.Delta{Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrder})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.purchaseorderscontroller.patchentity(v=AX.60)
ms:contentKeyID: 62203613
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PurchaseOrdersController.PatchEntity
dev_langs:
- CSharp
- C++
- VB
---

# PatchEntity Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Saves a purchase order to the local database.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.PickingAndReceiving)> _
Protected Overrides Function PatchEntity ( _
    key As String, _
    patch As Delta(Of PurchaseOrder) _
) As PurchaseOrder
'Usage
Dim key As String
Dim patch As Delta(Of PurchaseOrder)
Dim returnValue As PurchaseOrder

returnValue = Me.PatchEntity(key, _
    patch)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.PickingAndReceiving)]
protected override PurchaseOrder PatchEntity(
    string key,
    Delta<PurchaseOrder> patch
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::PickingAndReceiving)]
protected:
virtual PurchaseOrder^ PatchEntity(
    String^ key, 
    Delta<PurchaseOrder^>^ patch
) override
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - patch  
    Type: Delta\<PurchaseOrder\>  

#### Return Value

Type: PurchaseOrder  
The saved purchase order.  

## See Also

#### Reference

[PurchaseOrdersController Class](purchaseorderscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

