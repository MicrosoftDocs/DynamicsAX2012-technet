---
title: IGiftCardV1.UpdateGiftCard Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: UpdateGiftCard Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCardV1.UpdateGiftCard(System.Boolean@,System.String@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardTenderLineItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.igiftcardv1.updategiftcard(v=AX.60)
ms:contentKeyID: 47344245
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCardV1.UpdateGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# UpdateGiftCard Method

Deducts the amount paid with the gift card from the gift card's balance at the head office.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub UpdateGiftCard ( _
    ByRef updated As Boolean, _
    ByRef comment As String, _
    gcTenderLineItem As IGiftCardTenderLineItem _
)
'Usage
Dim instance As IGiftCardV1
Dim updated As Boolean
Dim comment As String
Dim gcTenderLineItem As IGiftCardTenderLineItem

instance.UpdateGiftCard(updated, comment, _
    gcTenderLineItem)
```

``` csharp
void UpdateGiftCard(
    ref bool updated,
    ref string comment,
    IGiftCardTenderLineItem gcTenderLineItem
)
```

``` c++
void UpdateGiftCard(
    bool% updated, 
    String^% comment, 
    IGiftCardTenderLineItem^ gcTenderLineItem
)
```

#### Parameters

  - updated  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - gcTenderLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardTenderLineItem](igiftcardtenderlineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IGiftCardV1 Interface](igiftcardv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

