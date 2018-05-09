---
title: IGiftCardTenderLineItemV1.IssuedDate Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IssuedDate Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardTenderLineItemV1.IssuedDate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.igiftcardtenderlineitemv1.issueddate(v=AX.60)
ms:contentKeyID: 49853085
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardTenderLineItemV1.IssuedDate
dev_langs:
- CSharp
- C++
- VB
---

# IssuedDate Property

The date when the gift certificate was issued.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IssuedDate As DateTime
    Get
    Set
'Usage
Dim instance As IGiftCardTenderLineItemV1
Dim value As DateTime

value = instance.IssuedDate

instance.IssuedDate = value
```

``` csharp
DateTime IssuedDate { get; set; }
```

``` c++
property DateTime IssuedDate {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[IGiftCardTenderLineItemV1 Interface](igiftcardtenderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

