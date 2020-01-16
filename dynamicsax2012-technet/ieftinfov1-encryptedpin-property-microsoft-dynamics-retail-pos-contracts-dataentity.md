---
title: IEFTInfoV1.EncryptedPIN Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: EncryptedPIN Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.EncryptedPIN
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.encryptedpin(v=AX.60)
ms:contentKeyID: 47128469
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.EncryptedPIN
dev_langs:
- CSharp
- C++
- VB
---

# EncryptedPIN Property

The encrypted card pin number that is collected from the hardware device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property EncryptedPIN As String
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As String

value = instance.EncryptedPIN

instance.EncryptedPIN = value
```

``` csharp
string EncryptedPIN { get; set; }
```

``` c++
property String^ EncryptedPIN {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IEFTInfoV1 Interface](ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

