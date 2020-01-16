---
title: IDialogV1.GenericSearch Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GenericSearch Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.GenericSearch(System.Data.DataTable,System.Data.DataRow@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idialogv1.genericsearch(v=AX.60)
ms:contentKeyID: 47343917
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.GenericSearch
dev_langs:
- CSharp
- C++
- VB
---

# GenericSearch Method

Displays generic search dialog box.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GenericSearch ( _
    dataTable As DataTable, _
    ByRef selectedRow As DataRow _
) As DialogResult
'Usage
Dim instance As IDialogV1
Dim dataTable As DataTable
Dim selectedRow As DataRow
Dim returnValue As DialogResult

returnValue = instance.GenericSearch(dataTable, _
    selectedRow)
```

``` csharp
DialogResult GenericSearch(
    DataTable dataTable,
    ref DataRow selectedRow
)
```

``` c++
DialogResult GenericSearch(
    DataTable^ dataTable, 
    DataRow^% selectedRow
)
```

#### Parameters

  - dataTable  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

<!-- end list -->

  - selectedRow  
    Type: [System.Data.DataRow](https://technet.microsoft.com/library/7f2d84ta\(v=ax.60\))  

#### Return Value

Type: [System.Windows.Forms.DialogResult](https://technet.microsoft.com/library/5ahe29t9\(v=ax.60\))  
One of the DialogResult values.  

## Remarks

This method is invoked by Dimension selection.

## See Also

#### Reference

[IDialogV1 Interface](idialogv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

