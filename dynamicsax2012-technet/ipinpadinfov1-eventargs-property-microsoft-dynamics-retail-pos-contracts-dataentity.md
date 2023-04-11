---
title: IPinPadInfoV1.EventArgs Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: EventArgs Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPinPadInfoV1.EventArgs
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipinpadinfov1.eventargs(v=AX.60)
ms:contentKeyID: 47128988
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPinPadInfoV1.EventArgs
dev_langs:
- CSharp
- C++
- VB
---

# EventArgs Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the event arguments.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property EventArgs As EventArgs
    Get
    Set
'Usage
Dim instance As IPinPadInfoV1
Dim value As EventArgs

value = instance.EventArgs

instance.EventArgs = value
```

``` csharp
EventArgs EventArgs { get; set; }
```

``` c++
property EventArgs^ EventArgs {
    EventArgs^ get ();
    void set (EventArgs^ value);
}
```

#### Property Value

Type: [System.EventArgs](https://technet.microsoft.com/library/118wxtk3\(v=ax.60\))  
The [System.EventArgs](https://technet.microsoft.com/library/118wxtk3\(v=ax.60\)) value.  

## See Also

#### Reference

[IPinPadInfoV1 Interface](ipinpadinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

