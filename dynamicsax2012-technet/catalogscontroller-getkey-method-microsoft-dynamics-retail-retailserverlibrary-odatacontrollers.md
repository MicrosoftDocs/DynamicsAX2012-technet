---
title: CatalogsController.GetKey Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetKey Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CatalogsController.GetKey(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.catalogscontroller.getkey(v=AX.60)
ms:contentKeyID: 62203036
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CatalogsController.GetKey
dev_langs:
- CSharp
- C++
- VB
---

# GetKey Method

Gets the key for a given product catalog.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetKey ( _
    entity As ProductCatalog _
) As Long
'Usage
Dim entity As ProductCatalog
Dim returnValue As Long

returnValue = Me.GetKey(entity)
```

``` csharp
protected override long GetKey(
    ProductCatalog entity
)
```

``` c++
protected:
virtual long long GetKey(
    ProductCatalog^ entity
) override
```

#### Parameters

  - entity  
    Type: ProductCatalog  

#### Return Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[CatalogsController Class](catalogscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

