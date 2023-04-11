---
title: IPosBatchStagingV1.OpenedAtTerminal Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: OpenedAtTerminal Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosBatchStagingV1.OpenedAtTerminal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iposbatchstagingv1.openedatterminal(v=AX.60)
ms:contentKeyID: 47129316
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosBatchStagingV1.OpenedAtTerminal
dev_langs:
- CSharp
- C++
- VB
---

# OpenedAtTerminal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the terminal ID where the batch was opened.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property OpenedAtTerminal As String
    Get
    Set
'Usage
Dim instance As IPosBatchStagingV1
Dim value As String

value = instance.OpenedAtTerminal

instance.OpenedAtTerminal = value
```

``` csharp
string OpenedAtTerminal { get; set; }
```

``` c++
property String^ OpenedAtTerminal {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IPosBatchStagingV1 Interface](iposbatchstagingv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

