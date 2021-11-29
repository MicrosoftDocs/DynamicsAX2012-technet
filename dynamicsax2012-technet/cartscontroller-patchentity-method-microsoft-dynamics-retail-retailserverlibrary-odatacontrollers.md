---
title: CartsController.PatchEntity Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: PatchEntity Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.PatchEntity(System.String,System.Web.Http.OData.Delta{Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.cartscontroller.patchentity(v=AX.60)
ms:contentKeyID: 62201957
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.PatchEntity
dev_langs:
- CSharp
- C++
- VB
---

# PatchEntity Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Patches Cart entity.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function PatchEntity ( _
    key As String, _
    patch As Delta(Of Cart) _
) As Cart
'Usage
Dim key As String
Dim patch As Delta(Of Cart)
Dim returnValue As Cart

returnValue = Me.PatchEntity(key, _
    patch)
```

``` csharp
protected override Cart PatchEntity(
    string key,
    Delta<Cart> patch
)
```

``` c++
protected:
virtual Cart^ PatchEntity(
    String^ key, 
    Delta<Cart^>^ patch
) override
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - patch  
    Type: Delta\<Cart\>  

#### Return Value

Type: Cart  
The pathed Cart.  

## See Also

#### Reference

[CartsController Class](cartscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

