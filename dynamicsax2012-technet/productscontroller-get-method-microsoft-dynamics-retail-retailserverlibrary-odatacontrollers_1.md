---
title: ProductsController.Get Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Get Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ProductsController.Get
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.productscontroller.get(v=AX.60)
ms:contentKeyID: 62202833
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

Searches for the product.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.ViewProductDetails)> _
Public Overrides Function Get As IQueryable(Of Product)
'Usage
Dim instance As ProductsController
Dim returnValue As IQueryable(Of Product)

returnValue = instance.Get()
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.ViewProductDetails)]
public override IQueryable<Product> Get()
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::ViewProductDetails)]
public:
virtual IQueryable<Product^>^ Get() override
```

#### Return Value

Type: [System.Linq.IQueryable](https://technet.microsoft.com/library/bb351562\(v=ax.60\))\<Product\>  
The [IQueryable](https://technet.microsoft.com/library/bb495796\(v=ax.60\)) of Product.  

## See Also

#### Reference

[ProductsController Class](productscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Get Overload](productscontroller-get-method-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

