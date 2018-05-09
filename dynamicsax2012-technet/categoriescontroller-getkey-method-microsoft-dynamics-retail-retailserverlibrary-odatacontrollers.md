---
title: CategoriesController.GetKey Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetKey Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CategoriesController.GetKey(Microsoft.Dynamics.Commerce.Runtime.DataModel.Category)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.categoriescontroller.getkey(v=AX.60)
ms:contentKeyID: 62203400
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CategoriesController.GetKey
dev_langs:
- CSharp
- C++
- VB
---

# GetKey Method

Gets the key for a given entity.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetKey ( _
    entity As Category _
) As Long
'Usage
Dim entity As Category
Dim returnValue As Long

returnValue = Me.GetKey(entity)
```

``` csharp
protected override long GetKey(
    Category entity
)
```

``` c++
protected:
virtual long long GetKey(
    Category^ entity
) override
```

#### Parameters

  - entity  
    Type: Category  

#### Return Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
The [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[CategoriesController Class](categoriescontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

