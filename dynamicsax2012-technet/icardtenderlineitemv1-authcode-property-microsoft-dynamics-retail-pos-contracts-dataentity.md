---
title: ICardTenderLineItemV1.AuthCode Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: AuthCode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardTenderLineItemV1.AuthCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardtenderlineitemv1.authcode(v=AX.60)
ms:contentKeyID: 49849060
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardTenderLineItemV1.AuthCode
dev_langs:
- CSharp
- C++
- VB
---

# AuthCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The authorization code received.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property AuthCode As String
    Get
    Set
'Usage
Dim instance As ICardTenderLineItemV1
Dim value As String

value = instance.AuthCode

instance.AuthCode = value
```

``` csharp
string AuthCode { get; set; }
```

``` c++
property String^ AuthCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ICardTenderLineItemV1 Interface](icardtenderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

