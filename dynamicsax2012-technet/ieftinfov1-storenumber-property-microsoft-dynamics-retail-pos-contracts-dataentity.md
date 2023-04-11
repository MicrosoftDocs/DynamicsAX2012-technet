---
title: IEFTInfoV1.StoreNumber Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: StoreNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.StoreNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.storenumber(v=AX.60)
ms:contentKeyID: 47128085
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.StoreNumber
dev_langs:
- CSharp
- C++
- VB
---

# StoreNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The store number.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property StoreNumber As String
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As String

value = instance.StoreNumber

instance.StoreNumber = value
```

``` csharp
string StoreNumber { get; set; }
```

``` c++
property String^ StoreNumber {
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

