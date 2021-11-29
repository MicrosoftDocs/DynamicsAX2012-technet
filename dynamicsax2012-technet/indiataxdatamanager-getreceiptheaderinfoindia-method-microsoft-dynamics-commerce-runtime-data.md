---
title: IndiaTaxDataManager.GetReceiptHeaderInfoIndia Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetReceiptHeaderInfoIndia Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDataManager.GetReceiptHeaderInfoIndia(Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.indiataxdatamanager.getreceiptheaderinfoindia(v=AX.60)
ms:contentKeyID: 62206303
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDataManager.GetReceiptHeaderInfoIndia
dev_langs:
- CSharp
- C++
- VB
---

# GetReceiptHeaderInfoIndia Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets Receipt Header India information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetReceiptHeaderInfoIndia ( _
    columns As ColumnSet _
) As ReceiptHeaderInfoIndia
'Usage
Dim instance As IndiaTaxDataManager
Dim columns As ColumnSet
Dim returnValue As ReceiptHeaderInfoIndia

returnValue = instance.GetReceiptHeaderInfoIndia(columns)
```

``` csharp
public ReceiptHeaderInfoIndia GetReceiptHeaderInfoIndia(
    ColumnSet columns
)
```

``` c++
public:
ReceiptHeaderInfoIndia^ GetReceiptHeaderInfoIndia(
    ColumnSet^ columns
)
```

#### Parameters

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptHeaderInfoIndia](receiptheaderinfoindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Receipt Header information.  

## See Also

#### Reference

[IndiaTaxDataManager Class](indiataxdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

