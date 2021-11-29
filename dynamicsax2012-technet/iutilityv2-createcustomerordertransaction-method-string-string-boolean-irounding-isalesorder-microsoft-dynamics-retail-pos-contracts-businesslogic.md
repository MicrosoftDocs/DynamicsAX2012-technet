---
title: IUtilityV2.CreateCustomerOrderTransaction Method (String, String, Boolean, IRounding, ISalesOrder) (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateCustomerOrderTransaction Method (String, String, Boolean, IRounding, ISalesOrder)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreateCustomerOrderTransaction(System.String,System.String,System.Boolean,Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding,Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrder)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv2.createcustomerordertransaction(v=AX.60)
ms:contentKeyID: 49831412
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateCustomerOrderTransaction Method (String, String, Boolean, IRounding, ISalesOrder)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateCustomerOrderTransaction ( _
    storeID As String, _
    storeCurrencyCode As String, _
    taxIncludedInPrice As Boolean, _
    rounding As IRounding, _
    salesOrderService As ISalesOrder _
) As ICustomerOrderTransaction
'Usage
Dim instance As IUtilityV2
Dim storeID As String
Dim storeCurrencyCode As String
Dim taxIncludedInPrice As Boolean
Dim rounding As IRounding
Dim salesOrderService As ISalesOrder
Dim returnValue As ICustomerOrderTransaction

returnValue = instance.CreateCustomerOrderTransaction(storeID, _
    storeCurrencyCode, taxIncludedInPrice, _
    rounding, salesOrderService)
```

``` csharp
ICustomerOrderTransaction CreateCustomerOrderTransaction(
    string storeID,
    string storeCurrencyCode,
    bool taxIncludedInPrice,
    IRounding rounding,
    ISalesOrder salesOrderService
)
```

``` c++
ICustomerOrderTransaction^ CreateCustomerOrderTransaction(
    String^ storeID, 
    String^ storeCurrencyCode, 
    bool taxIncludedInPrice, 
    IRounding^ rounding, 
    ISalesOrder^ salesOrderService
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

<!-- end list -->

  - salesOrderService  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrder](isalesorder-interface-microsoft-dynamics-retail-pos-contracts-services.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransaction](icustomerordertransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IUtilityV2 Interface](iutilityv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[CreateCustomerOrderTransaction Overload](iutilityv2-createcustomerordertransaction-method-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

