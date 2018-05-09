---
title: ICardV2.SelectCardType Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SelectCardType Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICardV2.SelectCardType(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo@,System.Boolean,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icardv2.selectcardtype(v=AX.60)
ms:contentKeyID: 49846749
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICardV2.SelectCardType
dev_langs:
- CSharp
- C++
- VB
---

# SelectCardType Method

Prompt to select card type.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SelectCardType ( _
    ByRef cardInfo As ICardInfo, _
    allowCancel As Boolean, _
    cardList As IEnumerable(Of ICardInfo) _
)
'Usage
Dim instance As ICardV2
Dim cardInfo As ICardInfo
Dim allowCancel As Boolean
Dim cardList As IEnumerable(Of ICardInfo)

instance.SelectCardType(cardInfo, allowCancel, _
    cardList)
```

``` csharp
void SelectCardType(
    ref ICardInfo cardInfo,
    bool allowCancel,
    IEnumerable<ICardInfo> cardList
)
```

``` c++
void SelectCardType(
    ICardInfo^% cardInfo, 
    bool allowCancel, 
    IEnumerable<ICardInfo^>^ cardList
)
```

#### Parameters

  - cardInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - allowCancel  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - cardList  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\>  

## See Also

#### Reference

[ICardV2 Interface](icardv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

