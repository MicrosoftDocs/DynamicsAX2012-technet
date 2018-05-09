---
title: IDialogV2.InventoryLookup Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: InventoryLookup Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV2.InventoryLookup(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.idialogv2.inventorylookup(v=AX.60)
ms:contentKeyID: 49837882
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV2.InventoryLookup
dev_langs:
- CSharp
- C++
- VB
---

# InventoryLookup Method

Displays inventory lookup form.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function InventoryLookup ( _
    itemOrVariantId As String _
) As DialogResult
'Usage
Dim instance As IDialogV2
Dim itemOrVariantId As String
Dim returnValue As DialogResult

returnValue = instance.InventoryLookup(itemOrVariantId)
```

``` csharp
DialogResult InventoryLookup(
    string itemOrVariantId
)
```

``` c++
DialogResult InventoryLookup(
    String^ itemOrVariantId
)
```

#### Parameters

  - itemOrVariantId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Windows.Forms.DialogResult](https://technet.microsoft.com/en-us/library/5ahe29t9\(v=ax.60\))  
Dialog result  

## See Also

#### Reference

[IDialogV2 Interface](idialogv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

