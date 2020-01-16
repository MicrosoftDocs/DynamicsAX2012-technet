---
title: IUtilityV2.CreateRetailTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateRetailTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreateRetailTransaction(System.String,System.String,System.Boolean,Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv2.createretailtransaction(v=AX.60)
ms:contentKeyID: 49826204
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreateRetailTransaction
dev_langs:
- CSharp
- C++
- VB
---

# CreateRetailTransaction Method

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateRetailTransaction ( _
    storeID As String, _
    storeCurrencyCode As String, _
    taxIncludedInPrice As Boolean, _
    rounding As IRounding _
) As IRetailTransaction
'Usage
Dim instance As IUtilityV2
Dim storeID As String
Dim storeCurrencyCode As String
Dim taxIncludedInPrice As Boolean
Dim rounding As IRounding
Dim returnValue As IRetailTransaction

returnValue = instance.CreateRetailTransaction(storeID, _
    storeCurrencyCode, taxIncludedInPrice, _
    rounding)
```

``` csharp
IRetailTransaction CreateRetailTransaction(
    string storeID,
    string storeCurrencyCode,
    bool taxIncludedInPrice,
    IRounding rounding
)
```

``` c++
IRetailTransaction^ CreateRetailTransaction(
    String^ storeID, 
    String^ storeCurrencyCode, 
    bool taxIncludedInPrice, 
    IRounding^ rounding
)
```

#### Parameters

  - storeID  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - taxIncludedInPrice  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - rounding  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding](irounding-interface-microsoft-dynamics-retail-pos-contracts-services.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IUtilityV2 Interface](iutilityv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

