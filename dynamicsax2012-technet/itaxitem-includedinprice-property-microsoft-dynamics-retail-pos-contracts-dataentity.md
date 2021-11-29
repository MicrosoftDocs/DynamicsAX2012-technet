---
title: ITaxItem.IncludedInPrice Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IncludedInPrice Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxItem.IncludedInPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxitem.includedinprice(v=AX.60)
ms:contentKeyID: 47129166
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxItem.IncludedInPrice
dev_langs:
- CSharp
- C++
- VB
---

# IncludedInPrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets whether the tax is included in the price.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IncludedInPrice As Boolean
    Get
    Set
'Usage
Dim instance As ITaxItem
Dim value As Boolean

value = instance.IncludedInPrice

instance.IncludedInPrice = value
```

``` csharp
bool IncludedInPrice { get; set; }
```

``` c++
property bool IncludedInPrice {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)) value.  

## See Also

#### Reference

[ITaxItem Interface](itaxitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

