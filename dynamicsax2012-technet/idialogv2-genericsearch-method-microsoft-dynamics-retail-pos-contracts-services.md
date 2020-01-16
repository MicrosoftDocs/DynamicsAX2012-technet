---
title: IDialogV2.GenericSearch Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GenericSearch Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV2.GenericSearch(System.Data.DataTable,System.Data.DataRow@,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idialogv2.genericsearch(v=AX.60)
ms:contentKeyID: 49827291
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV2.GenericSearch
dev_langs:
- CSharp
- C++
- VB
---

# GenericSearch Method

Generic search

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GenericSearch ( _
    dataTable As DataTable, _
    ByRef selectedRow As DataRow, _
    title As String _
) As DialogResult
'Usage
Dim instance As IDialogV2
Dim dataTable As DataTable
Dim selectedRow As DataRow
Dim title As String
Dim returnValue As DialogResult

returnValue = instance.GenericSearch(dataTable, _
    selectedRow, title)
```

``` csharp
DialogResult GenericSearch(
    DataTable dataTable,
    ref DataRow selectedRow,
    string title
)
```

``` c++
DialogResult GenericSearch(
    DataTable^ dataTable, 
    DataRow^% selectedRow, 
    String^ title
)
```

#### Parameters

  - dataTable  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

<!-- end list -->

  - selectedRow  
    Type: [System.Data.DataRow](https://technet.microsoft.com/library/7f2d84ta\(v=ax.60\))  

<!-- end list -->

  - title  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Windows.Forms.DialogResult](https://technet.microsoft.com/library/5ahe29t9\(v=ax.60\))  

## See Also

#### Reference

[IDialogV2 Interface](idialogv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

