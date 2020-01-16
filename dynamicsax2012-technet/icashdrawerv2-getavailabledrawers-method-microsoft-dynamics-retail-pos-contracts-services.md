---
title: ICashDrawerV2.GetAvailableDrawers Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetAvailableDrawers Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashDrawerV2.GetAvailableDrawers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icashdrawerv2.getavailabledrawers(v=AX.60)
ms:contentKeyID: 49835353
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashDrawerV2.GetAvailableDrawers
dev_langs:
- CSharp
- C++
- VB
---

# GetAvailableDrawers Method

Get the collection of properties of currently available cash drawers.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetAvailableDrawers As ICollection(Of Tuple)
'Usage
Dim instance As ICashDrawerV2
Dim returnValue As ICollection(Of Tuple)

returnValue = instance.GetAvailableDrawers()
```

``` csharp
ICollection<Tuple> GetAvailableDrawers()
```

``` c++
ICollection<Tuple^>^ GetAvailableDrawers()
```

#### Return Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<Tuple\>  
Collection of tuples containing Names and description of available drawers.  
Tuple.Item1 = Drawer name Tuple.Item2 = Drawer description  

## See Also

#### Reference

[ICashDrawerV2 Interface](icashdrawerv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

