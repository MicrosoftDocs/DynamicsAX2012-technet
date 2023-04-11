---
title: IGiftCardLineItemV1.SerialNumber Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SerialNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItemV1.SerialNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.igiftcardlineitemv1.serialnumber(v=AX.60)
ms:contentKeyID: 49847814
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItemV1.SerialNumber
dev_langs:
- CSharp
- C++
- VB
---

# SerialNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get or set gift card serial number

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SerialNumber As String
    Get
    Set
'Usage
Dim instance As IGiftCardLineItemV1
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

[IGiftCardLineItemV1 Interface](igiftcardlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

