---
title: IGiftCardTenderLineItemV1.IssuingTerminalId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IssuingTerminalId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardTenderLineItemV1.IssuingTerminalId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.igiftcardtenderlineitemv1.issuingterminalid(v=AX.60)
ms:contentKeyID: 49854880
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardTenderLineItemV1.IssuingTerminalId
dev_langs:
- CSharp
- C++
- VB
---

# IssuingTerminalId Property

The id of the terminal that issued the gift certificate.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IssuingTerminalId As String
    Get
    Set
'Usage
Dim instance As IGiftCardTenderLineItemV1
Dim value As String

value = instance.IssuingTerminalId

instance.IssuingTerminalId = value
```

``` csharp
string IssuingTerminalId { get; set; }
```

``` c++
property String^ IssuingTerminalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IGiftCardTenderLineItemV1 Interface](igiftcardtenderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

