---
title: IGiftCardV1.VoidGiftCard Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: VoidGiftCard Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCardV1.VoidGiftCard(System.Boolean@,System.String@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItem)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.igiftcardv1.voidgiftcard(v=AX.60)
ms:contentKeyID: 47343842
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IGiftCardV1.VoidGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# VoidGiftCard Method

Voids a gift card from a transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub VoidGiftCard ( _
    ByRef voided As Boolean, _
    ByRef comment As String, _
    gcLineItem As IGiftCardLineItem _
)
'Usage
Dim instance As IGiftCardV1
Dim voided As Boolean
Dim comment As String
Dim gcLineItem As IGiftCardLineItem

instance.VoidGiftCard(voided, comment, _
    gcLineItem)
```

``` csharp
void VoidGiftCard(
    ref bool voided,
    ref string comment,
    IGiftCardLineItem gcLineItem
)
```

``` c++
void VoidGiftCard(
    bool% voided, 
    String^% comment, 
    IGiftCardLineItem^ gcLineItem
)
```

#### Parameters

  - voided  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - gcLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItem](igiftcardlineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IGiftCardV1 Interface](igiftcardv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

