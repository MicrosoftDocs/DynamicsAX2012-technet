---
title: ISaleLineItemV1.DateToActivateItem Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: DateToActivateItem Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.DateToActivateItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.datetoactivateitem(v=AX.60)
ms:contentKeyID: 49832320
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.DateToActivateItem
dev_langs:
- CSharp
- C++
- VB
---

# DateToActivateItem Property

The date when the items becomes active

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property DateToActivateItem As DateTime
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As DateTime

value = instance.DateToActivateItem

instance.DateToActivateItem = value
```

``` csharp
DateTime DateToActivateItem { get; set; }
```

``` c++
property DateTime DateToActivateItem {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

