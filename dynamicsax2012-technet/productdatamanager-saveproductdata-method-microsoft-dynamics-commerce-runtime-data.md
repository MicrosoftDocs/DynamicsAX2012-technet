---
title: ProductDataManager.SaveProductData Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: SaveProductData Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.SaveProductData(System.Xml.Linq.XDocument)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.productdatamanager.saveproductdata(v=AX.60)
ms:contentKeyID: 62212513
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.SaveProductData
dev_langs:
- CSharp
- C++
- VB
---

# SaveProductData Method

Creates or updates the product data from the specified XML document.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub SaveProductData ( _
    productsXml As XDocument _
)
'Usage
Dim instance As ProductDataManager
Dim productsXml As XDocument

instance.SaveProductData(productsXml)
```

``` csharp
public void SaveProductData(
    XDocument productsXml
)
```

``` c++
public:
virtual void SaveProductData(
    XDocument^ productsXml
) sealed
```

#### Parameters

  - productsXml  
    Type: [System.Xml.Linq.XDocument](https://technet.microsoft.com/en-us/library/bb345449\(v=ax.60\))  

#### Implements

[IProductDataManager.SaveProductData(XDocument)](iproductdatamanager-saveproductdata-method-microsoft-dynamics-commerce-runtime-data.md)  

## Remarks

The [XDocument](https://technet.microsoft.com/en-us/library/bb345449\(v=ax.60\)) is retrieved from the Transaction Service API.

## See Also

#### Reference

[ProductDataManager Class](productdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

