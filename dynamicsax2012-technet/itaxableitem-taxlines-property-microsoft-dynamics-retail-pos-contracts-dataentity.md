---
title: ITaxableItem.TaxLines Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TaxLines Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.TaxLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.taxlines(v=AX.60)
ms:contentKeyID: 47129047
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.TaxLines
dev_langs:
- CSharp
- C++
- VB
---

# TaxLines Property

Gets the tax lines.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TaxLines As ICollection(Of ITaxItem)
    Get
'Usage
Dim instance As ITaxableItem
Dim value As ICollection(Of ITaxItem)

value = instance.TaxLines
```

``` csharp
ICollection<ITaxItem> TaxLines { get; }
```

``` c++
property ICollection<ITaxItem^>^ TaxLines {
    ICollection<ITaxItem^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ITaxItem](itaxitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\>  
The [System.Collections.Generic.ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)) value.  

## Remarks

This is not a read-only collection since we compute and add the tax lines as we go.

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

