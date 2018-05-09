---
title: IGiftCardLineItemV1.Date Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Date Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItemV1.Date
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.igiftcardlineitemv1.date(v=AX.60)
ms:contentKeyID: 49849801
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItemV1.Date
dev_langs:
- CSharp
- C++
- VB
---

# Date Property

Get or set date for this line item.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Date As DateTime
    Get
    Set
'Usage
Dim instance As IGiftCardLineItemV1
Dim value As DateTime

value = instance.Date

instance.Date = value
```

``` csharp
DateTime Date { get; set; }
```

``` c++
property DateTime Date {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[IGiftCardLineItemV1 Interface](igiftcardlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

