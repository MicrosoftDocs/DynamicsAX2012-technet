---
title: IDialogV1.PriceCheck Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PriceCheck Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.PriceCheck(System.Boolean,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.String@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idialogv1.pricecheck(v=AX.60)
ms:contentKeyID: 47343829
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.PriceCheck
dev_langs:
- CSharp
- C++
- VB
---

# PriceCheck Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Display a dialog box for the price-check operation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function PriceCheck ( _
    useScanner As Boolean, _
    posTransaction As IPosTransaction, _
    ByRef inputText As String _
) As DialogResult
'Usage
Dim instance As IDialogV1
Dim useScanner As Boolean
Dim posTransaction As IPosTransaction
Dim inputText As String
Dim returnValue As DialogResult

returnValue = instance.PriceCheck(useScanner, _
    posTransaction, inputText)
```

``` csharp
DialogResult PriceCheck(
    bool useScanner,
    IPosTransaction posTransaction,
    ref string inputText
)
```

``` c++
DialogResult PriceCheck(
    bool useScanner, 
    IPosTransaction^ posTransaction, 
    String^% inputText
)
```

#### Parameters

  - useScanner  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - inputText  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Windows.Forms.DialogResult](https://technet.microsoft.com/library/5ahe29t9\(v=ax.60\))  
One of the DialogResult values.  

## See Also

#### Reference

[IDialogV1 Interface](idialogv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

