---
title: IDialogV1.GenericLookup Method (DataTable, Int32, DataRow, String) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GenericLookup Method (DataTable, Int32, DataRow, String)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.GenericLookup(System.Data.DataTable,System.Int32,System.Data.DataRow@,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idialogv1.genericlookup(v=AX.60)
ms:contentKeyID: 47344382
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GenericLookup Method (DataTable, Int32, DataRow, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Displays generic lookup dialog box.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GenericLookup ( _
    dataTable As DataTable, _
    displayColumn As Integer, _
    ByRef selectedRow As DataRow, _
    defaultValue As String _
) As DialogResult
'Usage
Dim instance As IDialogV1
Dim dataTable As DataTable
Dim displayColumn As Integer
Dim selectedRow As DataRow
Dim defaultValue As String
Dim returnValue As DialogResult

returnValue = instance.GenericLookup(dataTable, _
    displayColumn, selectedRow, defaultValue)
```

``` csharp
DialogResult GenericLookup(
    DataTable dataTable,
    int displayColumn,
    ref DataRow selectedRow,
    string defaultValue
)
```

``` c++
DialogResult GenericLookup(
    DataTable^ dataTable, 
    int displayColumn, 
    DataRow^% selectedRow, 
    String^ defaultValue
)
```

#### Parameters

  - dataTable  
    Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  

<!-- end list -->

  - displayColumn  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - selectedRow  
    Type: [System.Data.DataRow](https://technet.microsoft.com/library/7f2d84ta\(v=ax.60\))  

<!-- end list -->

  - defaultValue  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Windows.Forms.DialogResult](https://technet.microsoft.com/library/5ahe29t9\(v=ax.60\))  
One of the DialogResult values.  

## Remarks

This method is invoked from the new customer dialog box.

## See Also

#### Reference

[IDialogV1 Interface](idialogv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[GenericLookup Overload](idialogv1-genericlookup-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

