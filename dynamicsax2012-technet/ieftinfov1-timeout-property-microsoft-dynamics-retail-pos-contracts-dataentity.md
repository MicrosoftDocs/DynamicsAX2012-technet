---
title: IEFTInfoV1.Timeout Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Timeout Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.Timeout
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.timeout(v=AX.60)
ms:contentKeyID: 47128384
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.Timeout
dev_langs:
- CSharp
- C++
- VB
---

# Timeout Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The number of seconds to wait for the EFT Server.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Timeout As Integer
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As Integer

value = instance.Timeout

instance.Timeout = value
```

``` csharp
int Timeout { get; set; }
```

``` c++
property int Timeout {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)) value.  

## See Also

#### Reference

[IEFTInfoV1 Interface](ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

