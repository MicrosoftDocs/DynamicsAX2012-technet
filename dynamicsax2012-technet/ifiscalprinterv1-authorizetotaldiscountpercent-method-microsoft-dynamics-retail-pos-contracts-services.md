---
title: IFiscalPrinterV1.AuthorizeTotalDiscountPercent Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AuthorizeTotalDiscountPercent Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.AuthorizeTotalDiscountPercent(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,System.Decimal,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.authorizetotaldiscountpercent(v=AX.60)
ms:contentKeyID: 62204993
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.AuthorizeTotalDiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# AuthorizeTotalDiscountPercent Method

Returns true if total discount percent is authorized.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function AuthorizeTotalDiscountPercent ( _
    retail As IRetailTransaction, _
    percentValue As Decimal, _
    maxPercentValue As Decimal _
) As Boolean
'Usage
Dim instance As IFiscalPrinterV1
Dim retail As IRetailTransaction
Dim percentValue As Decimal
Dim maxPercentValue As Decimal
Dim returnValue As Boolean

returnValue = instance.AuthorizeTotalDiscountPercent(retail, _
    percentValue, maxPercentValue)
```

``` csharp
bool AuthorizeTotalDiscountPercent(
    IRetailTransaction retail,
    decimal percentValue,
    decimal maxPercentValue
)
```

``` c++
bool AuthorizeTotalDiscountPercent(
    IRetailTransaction^ retail, 
    Decimal percentValue, 
    Decimal maxPercentValue
)
```

#### Parameters

  - retail  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - percentValue  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - maxPercentValue  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

