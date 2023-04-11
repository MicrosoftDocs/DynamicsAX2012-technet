---
title: IGiftCardTenderLineItemV1.IssuingStoreId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IssuingStoreId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardTenderLineItemV1.IssuingStoreId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.igiftcardtenderlineitemv1.issuingstoreid(v=AX.60)
ms:contentKeyID: 49819686
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardTenderLineItemV1.IssuingStoreId
dev_langs:
- CSharp
- C++
- VB
---

# IssuingStoreId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The id of the store that issued the gift certificate.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IssuingStoreId As String
    Get
    Set
'Usage
Dim instance As IGiftCardTenderLineItemV1
Dim value As String

value = instance.IssuingStoreId

instance.IssuingStoreId = value
```

``` csharp
string IssuingStoreId { get; set; }
```

``` c++
property String^ IssuingStoreId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IGiftCardTenderLineItemV1 Interface](igiftcardtenderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

