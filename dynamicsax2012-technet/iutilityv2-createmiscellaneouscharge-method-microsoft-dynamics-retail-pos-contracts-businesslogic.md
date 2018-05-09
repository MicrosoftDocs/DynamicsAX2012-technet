---
title: IUtilityV2.CreateMiscellaneousCharge Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateMiscellaneousCharge Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreateMiscellaneousCharge(System.Decimal,System.String,System.String,System.String,System.String,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv2.createmiscellaneouscharge(v=AX.60)
ms:contentKeyID: 49821822
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreateMiscellaneousCharge
dev_langs:
- CSharp
- C++
- VB
---

# CreateMiscellaneousCharge Method

Initializes a new instance of the [IMiscellaneousCharge](imiscellaneouscharge-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) class.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateMiscellaneousCharge ( _
    price As Decimal, _
    salesTaxGroupId As String, _
    taxGroupId As String, _
    miscChargeCodeId As String, _
    itemGroupId As String, _
    transaction As IRetailTransaction _
) As IMiscellaneousCharge
'Usage
Dim instance As IUtilityV2
Dim price As Decimal
Dim salesTaxGroupId As String
Dim taxGroupId As String
Dim miscChargeCodeId As String
Dim itemGroupId As String
Dim transaction As IRetailTransaction
Dim returnValue As IMiscellaneousCharge

returnValue = instance.CreateMiscellaneousCharge(price, _
    salesTaxGroupId, taxGroupId, miscChargeCodeId, _
    itemGroupId, transaction)
```

``` csharp
IMiscellaneousCharge CreateMiscellaneousCharge(
    decimal price,
    string salesTaxGroupId,
    string taxGroupId,
    string miscChargeCodeId,
    string itemGroupId,
    IRetailTransaction transaction
)
```

``` c++
IMiscellaneousCharge^ CreateMiscellaneousCharge(
    Decimal price, 
    String^ salesTaxGroupId, 
    String^ taxGroupId, 
    String^ miscChargeCodeId, 
    String^ itemGroupId, 
    IRetailTransaction^ transaction
)
```

#### Parameters

  - price  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - salesTaxGroupId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - taxGroupId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - miscChargeCodeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemGroupId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IMiscellaneousCharge](imiscellaneouscharge-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [IMiscellaneousCharge](imiscellaneouscharge-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[IUtilityV2 Interface](iutilityv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

