---
title: ITaxableItem.TaxGroupIdOriginal Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TaxGroupIdOriginal Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.TaxGroupIdOriginal
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.taxgroupidoriginal(v=AX.60)
ms:contentKeyID: 47128964
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.TaxGroupIdOriginal
dev_langs:
- CSharp
- C++
- VB
---

# TaxGroupIdOriginal Property

Gets or sets the original tax group ID.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TaxGroupIdOriginal As String
    Get
    Set
'Usage
Dim instance As ITaxableItem
Dim value As String

value = instance.TaxGroupIdOriginal

instance.TaxGroupIdOriginal = value
```

``` csharp
string TaxGroupIdOriginal { get; set; }
```

``` c++
property String^ TaxGroupIdOriginal {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The original tax group ID.  

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

