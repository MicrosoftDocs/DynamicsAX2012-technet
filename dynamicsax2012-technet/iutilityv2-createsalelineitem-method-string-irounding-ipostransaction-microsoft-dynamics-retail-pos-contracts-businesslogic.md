---
title: IUtilityV2.CreateSaleLineItem Method (String, IRounding, IPosTransaction) (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateSaleLineItem Method (String, IRounding, IPosTransaction)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV2.CreateSaleLineItem(System.String,Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv2.createsalelineitem(v=AX.60)
ms:contentKeyID: 49853322
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateSaleLineItem Method (String, IRounding, IPosTransaction)

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateSaleLineItem ( _
    storeCurrencyCode As String, _
    rounding As IRounding, _
    transaction As IPosTransaction _
) As ISaleLineItem
'Usage
Dim instance As IUtilityV2
Dim storeCurrencyCode As String
Dim rounding As IRounding
Dim transaction As IPosTransaction
Dim returnValue As ISaleLineItem

returnValue = instance.CreateSaleLineItem(storeCurrencyCode, _
    rounding, transaction)
```

``` csharp
ISaleLineItem CreateSaleLineItem(
    string storeCurrencyCode,
    IRounding rounding,
    IPosTransaction transaction
)
```

``` c++
ISaleLineItem^ CreateSaleLineItem(
    String^ storeCurrencyCode, 
    IRounding^ rounding, 
    IPosTransaction^ transaction
)
```

#### Parameters

  - storeCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - rounding  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding](irounding-interface-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IUtilityV2 Interface](iutilityv2-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[CreateSaleLineItem Overload](iutilityv2-createsalelineitem-method-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

