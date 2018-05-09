---
title: IPreTriggerResultV1.MessageId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: MessageId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResultV1.MessageId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.triggers.ipretriggerresultv1.messageid(v=AX.60)
ms:contentKeyID: 47128762
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResultV1.MessageId
dev_langs:
- CSharp
- C++
- VB
---

# MessageId Property

Gets or sets the message ID for dialog boxes. No message box is shown if message ID is set to'0'.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property MessageId As Integer
    Get
    Set
'Usage
Dim instance As IPreTriggerResultV1
Dim value As Integer

value = instance.MessageId

instance.MessageId = value
```

``` csharp
int MessageId { get; set; }
```

``` c++
property int MessageId {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
The [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)) value.  

## Remarks

After a message ID is set, it cannot be changed again.

## See Also

#### Reference

[IPreTriggerResultV1 Interface](ipretriggerresultv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

