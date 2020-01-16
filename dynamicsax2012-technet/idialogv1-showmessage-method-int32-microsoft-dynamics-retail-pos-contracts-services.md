---
title: IDialogV1.ShowMessage Method (Int32) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ShowMessage Method (Int32)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.ShowMessage(System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idialogv1.showmessage(v=AX.60)
ms:contentKeyID: 47343910
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ShowMessage Method (Int32)

The ShowMessage methods display an arbitrary message, either by an ID or literal text, with optional combinations of buttons and icons.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ShowMessage ( _
    messageId As Integer _
) As DialogResult
'Usage
Dim instance As IDialogV1
Dim messageId As Integer
Dim returnValue As DialogResult

returnValue = instance.ShowMessage(messageId)
```

``` csharp
DialogResult ShowMessage(
    int messageId
)
```

``` c++
DialogResult ShowMessage(
    int messageId
)
```

#### Parameters

  - messageId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.Windows.Forms.DialogResult](https://technet.microsoft.com/library/5ahe29t9\(v=ax.60\))  
One of the DialogResult values.  

## See Also

#### Reference

[IDialogV1 Interface](idialogv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[ShowMessage Overload](idialogv1-showmessage-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

