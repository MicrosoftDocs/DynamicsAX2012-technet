---
title: IItemV1.PbaItemConfigurable Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PbaItemConfigurable Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.PbaItemConfigurable
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.pbaitemconfigurable(v=AX.60)
ms:contentKeyID: 49842378
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.PbaItemConfigurable
dev_langs:
- CSharp
- C++
- VB
---

# PbaItemConfigurable Property

Gets or sets the pba item configurable.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PbaItemConfigurable As Integer
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As Integer

value = instance.PbaItemConfigurable

instance.PbaItemConfigurable = value
```

``` csharp
int PbaItemConfigurable { get; set; }
```

``` c++
property int PbaItemConfigurable {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
The pba item configurable.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

