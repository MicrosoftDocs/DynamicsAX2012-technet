---
title: IExtendedLogOnInfoV1.LogOnKey Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LogOnKey Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IExtendedLogOnInfoV1.LogOnKey
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iextendedlogoninfov1.logonkey(v=AX.60)
ms:contentKeyID: 49821273
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IExtendedLogOnInfoV1.LogOnKey
dev_langs:
- CSharp
- C++
- VB
---

# LogOnKey Property

Gets the device specific log on key.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property LogOnKey As String
    Get
'Usage
Dim instance As IExtendedLogOnInfoV1
Dim value As String

value = instance.LogOnKey
```

``` csharp
string LogOnKey { get; }
```

``` c++
property String^ LogOnKey {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

E.g. MSR card number, barcode or key from NFC/RFID device.

## See Also

#### Reference

[IExtendedLogOnInfoV1 Interface](iextendedlogoninfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

