---
title: SalesOrderDataManager.UpdateReturnQuantities Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: UpdateReturnQuantities Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.UpdateReturnQuantities(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salesorderdatamanager.updatereturnquantities(v=AX.60)
ms:contentKeyID: 62202265
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.UpdateReturnQuantities
dev_langs:
- CSharp
- C++
- VB
---

# UpdateReturnQuantities Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the return quantities of the returned sales lines based on the sales lines for return.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub UpdateReturnQuantities ( _
    salesLines As IEnumerable(Of SalesLine) _
)
'Usage
Dim instance As SalesOrderDataManager
Dim salesLines As IEnumerable(Of SalesLine)

instance.UpdateReturnQuantities(salesLines)
```

``` csharp
public void UpdateReturnQuantities(
    IEnumerable<SalesLine> salesLines
)
```

``` c++
public:
void UpdateReturnQuantities(
    IEnumerable<SalesLine^>^ salesLines
)
```

#### Parameters

  - salesLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SalesOrderDataManager Class](salesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

