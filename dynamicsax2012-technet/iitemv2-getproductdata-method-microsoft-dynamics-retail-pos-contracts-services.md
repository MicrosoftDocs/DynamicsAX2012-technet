---
title: IItemV2.GetProductData Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetProductData Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IItemV2.GetProductData(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iitemv2.getproductdata(v=AX.60)
ms:contentKeyID: 62206048
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IItemV2.GetProductData
dev_langs:
- CSharp
- C++
- VB
---

# GetProductData Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets list of Products from Product search in AX - Transaction Service call

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetProductData ( _
    itemIdRange As String _
) As XDocument
'Usage
Dim instance As IItemV2
Dim itemIdRange As String
Dim returnValue As XDocument

returnValue = instance.GetProductData(itemIdRange)
```

``` csharp
XDocument GetProductData(
    string itemIdRange
)
```

``` c++
XDocument^ GetProductData(
    String^ itemIdRange
)
```

#### Parameters

  - itemIdRange  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Xml.Linq.XDocument](https://technet.microsoft.com/library/bb345449\(v=ax.60\))  
Returns xml document of product data  

## See Also

#### Reference

[IItemV2 Interface](iitemv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

