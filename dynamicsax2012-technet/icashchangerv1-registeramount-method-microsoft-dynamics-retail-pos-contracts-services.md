---
title: ICashChangerV1.RegisterAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: RegisterAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.RegisterAmount(System.Decimal,System.String,System.Decimal@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.icashchangerv1.registeramount(v=AX.60)
ms:contentKeyID: 47344402
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICashChangerV1.RegisterAmount
dev_langs:
- CSharp
- C++
- VB
---

# RegisterAmount Method

Registers in to the transaction, that the amount has been entered into the cash machine.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function RegisterAmount ( _
    amountDue As Decimal, _
    receiptID As String, _
    ByRef amountRest As Decimal _
) As CashChangerReturn
'Usage
Dim instance As ICashChangerV1
Dim amountDue As Decimal
Dim receiptID As String
Dim amountRest As Decimal
Dim returnValue As CashChangerReturn

returnValue = instance.RegisterAmount(amountDue, _
    receiptID, amountRest)
```

``` csharp
CashChangerReturn RegisterAmount(
    decimal amountDue,
    string receiptID,
    ref decimal amountRest
)
```

``` c++
CashChangerReturn RegisterAmount(
    Decimal amountDue, 
    String^ receiptID, 
    Decimal% amountRest
)
```

#### Parameters

  - amountDue  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - receiptID  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amountRest  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.CashChangerReturn](cashchangerreturn-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
An instance of the CashChangerReturn enumeration.  

## See Also

#### Reference

[ICashChangerV1 Interface](icashchangerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

