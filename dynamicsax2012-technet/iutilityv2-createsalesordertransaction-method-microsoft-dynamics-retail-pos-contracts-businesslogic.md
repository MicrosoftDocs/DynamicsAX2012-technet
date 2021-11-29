---
title: IUtilityV2.CreateSalesOrderTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateSalesOrderTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreateSalesOrderTransaction(System.String,System.String,System.Boolean,Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv2.createsalesordertransaction(v=AX.60)
ms:contentKeyID: 49854848
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreateSalesOrderTransaction
dev_langs:
- CSharp
- C++
- VB
---

# CreateSalesOrderTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateSalesOrderTransaction ( _
    storeID As String, _
    storeCurrencyCode As String, _
    taxIncludedInPrice As Boolean, _
    rounding As IRounding _
) As ISalesOrderTransaction
'Usage
Dim instance As IUtilityV2
Dim storeID As String
Dim storeCurrencyCode As String
Dim taxIncludedInPrice As Boolean
Dim rounding As IRounding
Dim returnValue As ISalesOrderTransaction

returnValue = instance.CreateSalesOrderTransaction(storeID, _
    storeCurrencyCode, taxIncludedInPrice, _
    rounding)
```

``` csharp
ISalesOrderTransaction CreateSalesOrderTransaction(
    string storeID,
    string storeCurrencyCode,
    bool taxIncludedInPrice,
    IRounding rounding
)
```

``` c++
ISalesOrderTransaction^ CreateSalesOrderTransaction(
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

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISalesOrderTransaction](isalesordertransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IUtilityV2 Interface](iutilityv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

