---
title: ProductsController.GetKey Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetKey Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ProductsController.GetKey(Microsoft.Dynamics.Commerce.Runtime.DataModel.Product)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.productscontroller.getkey(v=AX.60)
ms:contentKeyID: 62203812
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ProductsController.GetKey
dev_langs:
- CSharp
- C++
- VB
---

# GetKey Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the key for a given product.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetKey ( _
    entity As Product _
) As Long
'Usage
Dim entity As Product
Dim returnValue As Long

returnValue = Me.GetKey(entity)
```

``` csharp
protected override long GetKey(
    Product entity
)
```

``` c++
protected:
virtual long long GetKey(
    Product^ entity
) override
```

#### Parameters

  - entity  
    Type: Product  

#### Return Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductsController Class](productscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

