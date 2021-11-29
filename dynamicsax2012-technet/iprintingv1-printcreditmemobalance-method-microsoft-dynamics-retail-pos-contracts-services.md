---
title: IPrintingV1.PrintCreditMemoBalance Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintCreditMemoBalance Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintCreditMemoBalance(Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType,System.Decimal,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprintingv1.printcreditmemobalance(v=AX.60)
ms:contentKeyID: 47343914
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintCreditMemoBalance
dev_langs:
- CSharp
- C++
- VB
---

# PrintCreditMemoBalance Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Prints credit memo balance.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintCreditMemoBalance ( _
    formType As FormType, _
    balance As Decimal, _
    copyReceipt As Boolean _
)
'Usage
Dim instance As IPrintingV1
Dim formType As FormType
Dim balance As Decimal
Dim copyReceipt As Boolean

instance.PrintCreditMemoBalance(formType, _
    balance, copyReceipt)
```

``` csharp
void PrintCreditMemoBalance(
    FormType formType,
    decimal balance,
    bool copyReceipt
)
```

``` c++
void PrintCreditMemoBalance(
    FormType formType, 
    Decimal balance, 
    bool copyReceipt
)
```

#### Parameters

  - formType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType](formtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - balance  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - copyReceipt  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IPrintingV1 Interface](iprintingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

