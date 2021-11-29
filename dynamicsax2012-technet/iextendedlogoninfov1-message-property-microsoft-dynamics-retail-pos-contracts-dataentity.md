---
title: IExtendedLogOnInfoV1.Message Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Message Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IExtendedLogOnInfoV1.Message
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iextendedlogoninfov1.message(v=AX.60)
ms:contentKeyID: 49841426
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IExtendedLogOnInfoV1.Message
dev_langs:
- CSharp
- C++
- VB
---

# Message Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the message sent by device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Message As String
    Get
'Usage
Dim instance As IExtendedLogOnInfoV1
Dim value As String

value = instance.Message
```

``` csharp
string Message { get; }
```

``` c++
property String^ Message {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IExtendedLogOnInfoV1 Interface](iextendedlogoninfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

