---
title: IPreTriggerResultV1.ContinueOperation Property  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: ContinueOperation Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResultV1.ContinueOperation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.ipretriggerresultv1.continueoperation(v=AX.60)
ms:contentKeyID: 47129145
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResultV1.ContinueOperation
dev_langs:
- CSharp
- C++
- VB
---

# ContinueOperation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the operation run behavior. Set to 'false' to request abort.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ContinueOperation As Boolean
    Get
    Set
'Usage
Dim instance As IPreTriggerResultV1
Dim value As Boolean

value = instance.ContinueOperation

instance.ContinueOperation = value
```

``` csharp
bool ContinueOperation { get; set; }
```

``` c++
property bool ContinueOperation {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)) value.  

## Remarks

After ContinueOperation is set to false, it cannot be set to true again.

## See Also

#### Reference

[IPreTriggerResultV1 Interface](ipretriggerresultv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

