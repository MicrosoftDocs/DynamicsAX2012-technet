---
title: ICardInfoV1.SecurityCode Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SecurityCode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.SecurityCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov1.securitycode(v=AX.60)
ms:contentKeyID: 47128024
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.SecurityCode
dev_langs:
- CSharp
- C++
- VB
---

# SecurityCode Property

The security code associated with the card.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SecurityCode As String
    Get
    Set
'Usage
Dim instance As ICardInfoV1
Dim value As String

value = instance.SecurityCode

instance.SecurityCode = value
```

``` csharp
string SecurityCode { get; set; }
```

``` c++
property String^ SecurityCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[ICardInfoV1 Interface](icardinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

