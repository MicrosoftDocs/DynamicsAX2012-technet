---
title: IItemV1.StopExplode Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: StopExplode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.StopExplode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.stopexplode(v=AX.60)
ms:contentKeyID: 49836766
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.StopExplode
dev_langs:
- CSharp
- C++
- VB
---

# StopExplode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the stop explode.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property StopExplode As Integer
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As Integer

value = instance.StopExplode

instance.StopExplode = value
```

``` csharp
int StopExplode { get; set; }
```

``` c++
property int StopExplode {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The stop explode.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

