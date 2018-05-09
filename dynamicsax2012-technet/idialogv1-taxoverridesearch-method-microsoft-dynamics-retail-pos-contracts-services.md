---
title: IDialogV1.TaxOverrideSearch Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: TaxOverrideSearch Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.TaxOverrideSearch(System.Int32,System.Int32,System.String@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.idialogv1.taxoverridesearch(v=AX.60)
ms:contentKeyID: 47344184
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.TaxOverrideSearch
dev_langs:
- CSharp
- C++
- VB
---

# TaxOverrideSearch Method

Tax override search.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function TaxOverrideSearch ( _
    howManyRows As Integer, _
    overrideBy As Integer, _
    ByRef selectedTaxCodeId As String _
) As DialogResult
'Usage
Dim instance As IDialogV1
Dim howManyRows As Integer
Dim overrideBy As Integer
Dim selectedTaxCodeId As String
Dim returnValue As DialogResult

returnValue = instance.TaxOverrideSearch(howManyRows, _
    overrideBy, selectedTaxCodeId)
```

``` csharp
DialogResult TaxOverrideSearch(
    int howManyRows,
    int overrideBy,
    ref string selectedTaxCodeId
)
```

``` c++
DialogResult TaxOverrideSearch(
    int howManyRows, 
    int overrideBy, 
    String^% selectedTaxCodeId
)
```

#### Parameters

  - howManyRows  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - overrideBy  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - selectedTaxCodeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Windows.Forms.DialogResult](https://technet.microsoft.com/en-us/library/5ahe29t9\(v=ax.60\))  
One of the DialogResult values.  

## See Also

#### Reference

[IDialogV1 Interface](idialogv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

