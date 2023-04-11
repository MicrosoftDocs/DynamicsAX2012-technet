---
title: IGiftCardTenderLineItemV1.SerialNumber Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SerialNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardTenderLineItemV1.SerialNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.igiftcardtenderlineitemv1.serialnumber(v=AX.60)
ms:contentKeyID: 49854411
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardTenderLineItemV1.SerialNumber
dev_langs:
- CSharp
- C++
- VB
---

# SerialNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The serialnumber of the gift certificate.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SerialNumber As String
    Get
    Set
'Usage
Dim instance As IGiftCardTenderLineItemV1
Dim value As String

value = instance.SerialNumber

instance.SerialNumber = value
```

``` csharp
string SerialNumber { get; set; }
```

``` c++
property String^ SerialNumber {
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

