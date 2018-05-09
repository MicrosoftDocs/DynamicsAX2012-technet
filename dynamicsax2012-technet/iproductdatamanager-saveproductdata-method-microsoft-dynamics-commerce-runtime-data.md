---
title: IProductDataManager.SaveProductData Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: SaveProductData Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IProductDataManager.SaveProductData(System.Xml.Linq.XDocument)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.iproductdatamanager.saveproductdata(v=AX.60)
ms:contentKeyID: 62213320
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IProductDataManager.SaveProductData
dev_langs:
- CSharp
- C++
- VB
---

# SaveProductData Method

Inserts the product data from the specified XML document.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub SaveProductData ( _
    productsXml As XDocument _
)
'Usage
Dim instance As IProductDataManager
Dim productsXml As XDocument

instance.SaveProductData(productsXml)
```

``` csharp
void SaveProductData(
    XDocument productsXml
)
```

``` c++
void SaveProductData(
    XDocument^ productsXml
)
```

#### Parameters

  - productsXml  
    Type: [System.Xml.Linq.XDocument](https://technet.microsoft.com/en-us/library/bb345449\(v=ax.60\))  

## Remarks

The [XDocument](https://technet.microsoft.com/en-us/library/bb345449\(v=ax.60\)) is retrieved from the Transaction Service API.

## See Also

#### Reference

[IProductDataManager Interface](iproductdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

