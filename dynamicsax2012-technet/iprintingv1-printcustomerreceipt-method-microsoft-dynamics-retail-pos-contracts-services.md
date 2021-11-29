---
title: IPrintingV1.PrintCustomerReceipt Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintCustomerReceipt Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintCustomerReceipt(Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItem,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprintingv1.printcustomerreceipt(v=AX.60)
ms:contentKeyID: 47344458
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintCustomerReceipt
dev_langs:
- CSharp
- C++
- VB
---

# PrintCustomerReceipt Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Prints custom receipt.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintCustomerReceipt ( _
    formType As FormType, _
    posTransaction As IPosTransaction, _
    tenderLineItem As ITenderLineItem, _
    copyReceipt As Boolean _
)
'Usage
Dim instance As IPrintingV1
Dim formType As FormType
Dim posTransaction As IPosTransaction
Dim tenderLineItem As ITenderLineItem
Dim copyReceipt As Boolean

instance.PrintCustomerReceipt(formType, _
    posTransaction, tenderLineItem, _
    copyReceipt)
```

``` csharp
void PrintCustomerReceipt(
    FormType formType,
    IPosTransaction posTransaction,
    ITenderLineItem tenderLineItem,
    bool copyReceipt
)
```

``` c++
void PrintCustomerReceipt(
    FormType formType, 
    IPosTransaction^ posTransaction, 
    ITenderLineItem^ tenderLineItem, 
    bool copyReceipt
)
```

#### Parameters

  - formType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType](formtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - tenderLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItem](itenderlineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - copyReceipt  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IPrintingV1 Interface](iprintingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

