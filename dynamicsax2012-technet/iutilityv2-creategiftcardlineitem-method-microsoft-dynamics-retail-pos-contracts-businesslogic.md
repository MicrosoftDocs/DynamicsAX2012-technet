---
title: IUtilityV2.CreateGiftCardLineItem Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateGiftCardLineItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreateGiftCardLineItem(System.String,Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv2.creategiftcardlineitem(v=AX.60)
ms:contentKeyID: 49844940
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreateGiftCardLineItem
dev_langs:
- CSharp
- C++
- VB
---

# CreateGiftCardLineItem Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateGiftCardLineItem ( _
    storeCurrencyCode As String, _
    rounding As IRounding, _
    transaction As IRetailTransaction _
) As IGiftCardLineItem
'Usage
Dim instance As IUtilityV2
Dim storeCurrencyCode As String
Dim rounding As IRounding
Dim transaction As IRetailTransaction
Dim returnValue As IGiftCardLineItem

returnValue = instance.CreateGiftCardLineItem(storeCurrencyCode, _
    rounding, transaction)
```

``` csharp
IGiftCardLineItem CreateGiftCardLineItem(
    string storeCurrencyCode,
    IRounding rounding,
    IRetailTransaction transaction
)
```

``` c++
IGiftCardLineItem^ CreateGiftCardLineItem(
    String^ storeCurrencyCode, 
    IRounding^ rounding, 
    IRetailTransaction^ transaction
)
```

#### Parameters

  - storeCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - rounding  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding](irounding-interface-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IGiftCardLineItem](igiftcardlineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IUtilityV2 Interface](iutilityv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

