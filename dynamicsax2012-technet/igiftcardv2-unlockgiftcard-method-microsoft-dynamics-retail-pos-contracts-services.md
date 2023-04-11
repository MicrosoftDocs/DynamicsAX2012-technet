---
title: IGiftCardV2.UnlockGiftCard Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: UnlockGiftCard Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCardV2.UnlockGiftCard(System.Boolean@,System.String@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.igiftcardv2.unlockgiftcard(v=AX.60)
ms:contentKeyID: 62204507
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCardV2.UnlockGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# UnlockGiftCard Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Releases the gift card.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub UnlockGiftCard ( _
    ByRef released As Boolean, _
    ByRef comment As String, _
    gcLineItem As IGiftCardLineItem _
)
'Usage
Dim instance As IGiftCardV2
Dim released As Boolean
Dim comment As String
Dim gcLineItem As IGiftCardLineItem

instance.UnlockGiftCard(released, comment, _
    gcLineItem)
```

``` csharp
void UnlockGiftCard(
    ref bool released,
    ref string comment,
    IGiftCardLineItem gcLineItem
)
```

``` c++
void UnlockGiftCard(
    bool% released, 
    String^% comment, 
    IGiftCardLineItem^ gcLineItem
)
```

#### Parameters

  - released  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - gcLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItem](igiftcardlineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IGiftCardV2 Interface](igiftcardv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

