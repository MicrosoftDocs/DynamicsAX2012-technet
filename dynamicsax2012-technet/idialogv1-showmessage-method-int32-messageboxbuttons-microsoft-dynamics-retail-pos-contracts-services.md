---
title: IDialogV1.ShowMessage Method (Int32, MessageBoxButtons) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ShowMessage Method (Int32, MessageBoxButtons)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDialogV1.ShowMessage(System.Int32,System.Windows.Forms.MessageBoxButtons)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idialogv1.showmessage(v=AX.60)
ms:contentKeyID: 47343945
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ShowMessage Method (Int32, MessageBoxButtons)

Shows the message.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ShowMessage ( _
    messageId As Integer, _
    msgBoxButtons As MessageBoxButtons _
) As DialogResult
'Usage
Dim instance As IDialogV1
Dim messageId As Integer
Dim msgBoxButtons As MessageBoxButtons
Dim returnValue As DialogResult

returnValue = instance.ShowMessage(messageId, _
    msgBoxButtons)
```

``` csharp
DialogResult ShowMessage(
    int messageId,
    MessageBoxButtons msgBoxButtons
)
```

``` c++
DialogResult ShowMessage(
    int messageId, 
    MessageBoxButtons msgBoxButtons
)
```

#### Parameters

  - messageId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - msgBoxButtons  
    Type: [System.Windows.Forms.MessageBoxButtons](https://technet.microsoft.com/library/a29zcz90\(v=ax.60\))  

#### Return Value

Type: [System.Windows.Forms.DialogResult](https://technet.microsoft.com/library/5ahe29t9\(v=ax.60\))  
One of the DialogResult values.  

## See Also

#### Reference

[IDialogV1 Interface](idialogv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[ShowMessage Overload](idialogv1-showmessage-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

