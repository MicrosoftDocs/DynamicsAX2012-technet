---
title: IDialogV1.TenderDeclaration Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: TenderDeclaration Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.TenderDeclaration(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.idialogv1.tenderdeclaration(v=AX.60)
ms:contentKeyID: 47343949
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.TenderDeclaration
dev_langs:
- CSharp
- C++
- VB
---

# TenderDeclaration Method

This method is invoked from bank drop, safe drop, and tender declaration operations.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function TenderDeclaration ( _
    posTransaction As IPosTransaction _
) As DialogResult
'Usage
Dim instance As IDialogV1
Dim posTransaction As IPosTransaction
Dim returnValue As DialogResult

returnValue = instance.TenderDeclaration(posTransaction)
```

``` csharp
DialogResult TenderDeclaration(
    IPosTransaction posTransaction
)
```

``` c++
DialogResult TenderDeclaration(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Windows.Forms.DialogResult](https://technet.microsoft.com/en-us/library/5ahe29t9\(v=ax.60\))  
One of the DialogResult values.  

## See Also

#### Reference

[IDialogV1 Interface](idialogv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

