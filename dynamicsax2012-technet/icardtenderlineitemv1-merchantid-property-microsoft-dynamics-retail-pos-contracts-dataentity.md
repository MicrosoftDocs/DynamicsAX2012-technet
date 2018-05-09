---
title: ICardTenderLineItemV1.MerchantId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: MerchantId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardTenderLineItemV1.MerchantId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardtenderlineitemv1.merchantid(v=AX.60)
ms:contentKeyID: 49834286
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardTenderLineItemV1.MerchantId
dev_langs:
- CSharp
- C++
- VB
---

# MerchantId Property

The merchant id used for authorization.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property MerchantId As String
    Get
    Set
'Usage
Dim instance As ICardTenderLineItemV1
Dim value As String

value = instance.MerchantId

instance.MerchantId = value
```

``` csharp
string MerchantId { get; set; }
```

``` c++
property String^ MerchantId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ICardTenderLineItemV1 Interface](icardtenderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

