---
title: IExtendedLogOnInfoV1.LogOnType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LogOnType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IExtendedLogOnInfoV1.LogOnType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iextendedlogoninfov1.logontype(v=AX.60)
ms:contentKeyID: 49837080
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IExtendedLogOnInfoV1.LogOnType
dev_langs:
- CSharp
- C++
- VB
---

# LogOnType Property

Gets the type of the log on.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property LogOnType As ExtendedLogOnType
    Get
'Usage
Dim instance As IExtendedLogOnInfoV1
Dim value As ExtendedLogOnType

value = instance.LogOnType
```

``` csharp
ExtendedLogOnType LogOnType { get; }
```

``` c++
property ExtendedLogOnType LogOnType {
    ExtendedLogOnType get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ExtendedLogOnType](extendedlogontype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
Returns [ExtendedLogOnType](extendedlogontype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md).  

## See Also

#### Reference

[IExtendedLogOnInfoV1 Interface](iextendedlogoninfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

