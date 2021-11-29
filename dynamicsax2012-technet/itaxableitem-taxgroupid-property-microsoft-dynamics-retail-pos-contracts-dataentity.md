---
title: ITaxableItem.TaxGroupId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TaxGroupId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.TaxGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.taxgroupid(v=AX.60)
ms:contentKeyID: 47129325
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.TaxGroupId
dev_langs:
- CSharp
- C++
- VB
---

# TaxGroupId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax group ID.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TaxGroupId As String
    Get
    Set
'Usage
Dim instance As ITaxableItem
Dim value As String

value = instance.TaxGroupId

instance.TaxGroupId = value
```

``` csharp
string TaxGroupId { get; set; }
```

``` c++
property String^ TaxGroupId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The tax group ID.  

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

