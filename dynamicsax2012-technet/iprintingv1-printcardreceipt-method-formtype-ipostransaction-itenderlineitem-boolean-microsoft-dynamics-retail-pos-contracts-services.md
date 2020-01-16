---
title: IPrintingV1.PrintCardReceipt Method (FormType, IPosTransaction, ITenderLineItem, Boolean) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintCardReceipt Method (FormType, IPosTransaction, ITenderLineItem, Boolean)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintCardReceipt(Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItem,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprintingv1.printcardreceipt(v=AX.60)
ms:contentKeyID: 47344137
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PrintCardReceipt Method (FormType, IPosTransaction, ITenderLineItem, Boolean)

Prints the card payment receipt.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintCardReceipt ( _
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

instance.PrintCardReceipt(formType, posTransaction, _
    tenderLineItem, copyReceipt)
```

``` csharp
void PrintCardReceipt(
    FormType formType,
    IPosTransaction posTransaction,
    ITenderLineItem tenderLineItem,
    bool copyReceipt
)
```

``` c++
void PrintCardReceipt(
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

[PrintCardReceipt Overload](iprintingv1-printcardreceipt-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

