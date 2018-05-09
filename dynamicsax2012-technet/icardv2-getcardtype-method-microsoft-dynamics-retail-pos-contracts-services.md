---
title: ICardV2.GetCardType Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetCardType Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICardV2.GetCardType(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo@,System.Boolean,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Pos.Contracts.Services.CardTypes})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icardv2.getcardtype(v=AX.60)
ms:contentKeyID: 49846379
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICardV2.GetCardType
dev_langs:
- CSharp
- C++
- VB
---

# GetCardType Method

Find card type for specific card info from database.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetCardType ( _
    ByRef cardInfo As ICardInfo, _
    allowCancel As Boolean, _
    exclusionList As IEnumerable(Of CardTypes) _
)
'Usage
Dim instance As ICardV2
Dim cardInfo As ICardInfo
Dim allowCancel As Boolean
Dim exclusionList As IEnumerable(Of CardTypes)

instance.GetCardType(cardInfo, allowCancel, _
    exclusionList)
```

``` csharp
void GetCardType(
    ref ICardInfo cardInfo,
    bool allowCancel,
    IEnumerable<CardTypes> exclusionList
)
```

``` c++
void GetCardType(
    ICardInfo^% cardInfo, 
    bool allowCancel, 
    IEnumerable<CardTypes>^ exclusionList
)
```

#### Parameters

  - cardInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - allowCancel  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - exclusionList  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[CardTypes](cardtypes-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)\>  

## See Also

#### Reference

[ICardV2 Interface](icardv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

