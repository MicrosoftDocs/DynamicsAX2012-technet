---
title: ICustomerDiscountItemV1.ItemDiscountGroup Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ItemDiscountGroup Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerDiscountItemV1.ItemDiscountGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerdiscountitemv1.itemdiscountgroup(v=AX.60)
ms:contentKeyID: 49851731
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerDiscountItemV1.ItemDiscountGroup
dev_langs:
- CSharp
- C++
- VB
---

# ItemDiscountGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The discount group of the item

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ItemDiscountGroup As String
    Get
    Set
'Usage
Dim instance As ICustomerDiscountItemV1
Dim value As String

value = instance.ItemDiscountGroup

instance.ItemDiscountGroup = value
```

``` csharp
string ItemDiscountGroup { get; set; }
```

``` c++
property String^ ItemDiscountGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ICustomerDiscountItemV1 Interface](icustomerdiscountitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

