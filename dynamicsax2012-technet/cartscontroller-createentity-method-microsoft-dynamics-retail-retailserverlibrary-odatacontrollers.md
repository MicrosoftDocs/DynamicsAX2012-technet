---
title: CartsController.CreateEntity Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: CreateEntity Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.CreateEntity(Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.cartscontroller.createentity(v=AX.60)
ms:contentKeyID: 62202135
author: Khairunj
ms.author: daxcpft
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.CreateEntity
dev_langs:
- CSharp
- C++
- VB
---

# CreateEntity Method

Creates Cart entity.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function CreateEntity ( _
    entity As Cart _
) As Cart
'Usage
Dim entity As Cart
Dim returnValue As Cart

returnValue = Me.CreateEntity(entity)
```

``` csharp
protected override Cart CreateEntity(
    Cart entity
)
```

``` c++
protected:
virtual Cart^ CreateEntity(
    Cart^ entity
) override
```

#### Parameters

  - entity  
    Type: Cart  

#### Return Value

Type: Cart  
The Cart.  

## See Also

#### Reference

[CartsController Class](cartscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

