---
title: CartsController.UpdateEntity Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: UpdateEntity Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.UpdateEntity(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.cartscontroller.updateentity(v=AX.60)
ms:contentKeyID: 62202185
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.UpdateEntity
dev_langs:
- CSharp
- C++
- VB
---

# UpdateEntity Method

Updates Cart entity.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function UpdateEntity ( _
    key As String, _
    update As Cart _
) As Cart
'Usage
Dim key As String
Dim update As Cart
Dim returnValue As Cart

returnValue = Me.UpdateEntity(key, _
    update)
```

``` csharp
protected override Cart UpdateEntity(
    string key,
    Cart update
)
```

``` c++
protected:
virtual Cart^ UpdateEntity(
    String^ key, 
    Cart^ update
) override
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - update  
    Type: Cart  

#### Return Value

Type: Cart  
The Cart.  

## See Also

#### Reference

[CartsController Class](cartscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

