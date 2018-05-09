---
title: IDialogV1.ItemSearch Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ItemSearch Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.ItemSearch(System.Int32,System.String@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.idialogv1.itemsearch(v=AX.60)
ms:contentKeyID: 47344377
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.ItemSearch
dev_langs:
- CSharp
- C++
- VB
---

# ItemSearch Method

Returns the DialogResult values.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ItemSearch ( _
    howManyRows As Integer, _
    ByRef selectedItemID As String _
) As DialogResult
'Usage
Dim instance As IDialogV1
Dim howManyRows As Integer
Dim selectedItemID As String
Dim returnValue As DialogResult

returnValue = instance.ItemSearch(howManyRows, _
    selectedItemID)
```

``` csharp
DialogResult ItemSearch(
    int howManyRows,
    ref string selectedItemID
)
```

``` c++
DialogResult ItemSearch(
    int howManyRows, 
    String^% selectedItemID
)
```

#### Parameters

  - howManyRows  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - selectedItemID  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Windows.Forms.DialogResult](https://technet.microsoft.com/en-us/library/5ahe29t9\(v=ax.60\))  
One of the DialogResult values  

## See Also

#### Reference

[IDialogV1 Interface](idialogv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

