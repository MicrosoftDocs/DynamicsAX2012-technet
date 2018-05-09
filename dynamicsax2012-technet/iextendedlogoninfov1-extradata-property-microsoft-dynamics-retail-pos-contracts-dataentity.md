---
title: IExtendedLogOnInfoV1.ExtraData Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ExtraData Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IExtendedLogOnInfoV1.ExtraData
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iextendedlogoninfov1.extradata(v=AX.60)
ms:contentKeyID: 49833078
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IExtendedLogOnInfoV1.ExtraData
dev_langs:
- CSharp
- C++
- VB
---

# ExtraData Property

Gets the device specific extra data.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property ExtraData As Byte()
    Get
'Usage
Dim instance As IExtendedLogOnInfoV1
Dim value As Byte()

value = instance.ExtraData
```

``` csharp
byte[] ExtraData { get; }
```

``` c++
property array<unsigned char>^ ExtraData {
    array<unsigned char>^ get ();
}
```

#### Property Value

Type: [System.Byte](https://technet.microsoft.com/en-us/library/yyb1w04y\(v=ax.60\))\[\]  
Returns [Byte](https://technet.microsoft.com/en-us/library/yyb1w04y\(v=ax.60\)).  

## See Also

#### Reference

[IExtendedLogOnInfoV1 Interface](iextendedlogoninfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

