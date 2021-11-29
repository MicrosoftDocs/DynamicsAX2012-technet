---
title: IPrintingV2.PrintReturnLabel Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintReturnLabel Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV2.PrintReturnLabel(Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprintingv2.printreturnlabel(v=AX.60)
ms:contentKeyID: 62205447
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV2.PrintReturnLabel
dev_langs:
- CSharp
- C++
- VB
---

# PrintReturnLabel Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Prints the return label.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintReturnLabel ( _
    formType As FormType, _
    posTransaction As IPosTransaction, _
    saleItem As ISaleLineItem, _
    copyReceipt As Boolean _
)
'Usage
Dim instance As IPrintingV2
Dim formType As FormType
Dim posTransaction As IPosTransaction
Dim saleItem As ISaleLineItem
Dim copyReceipt As Boolean

instance.PrintReturnLabel(formType, posTransaction, _
    saleItem, copyReceipt)
```

``` csharp
void PrintReturnLabel(
    FormType formType,
    IPosTransaction posTransaction,
    ISaleLineItem saleItem,
    bool copyReceipt
)
```

``` c++
void PrintReturnLabel(
    FormType formType, 
    IPosTransaction^ posTransaction, 
    ISaleLineItem^ saleItem, 
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

  - saleItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - copyReceipt  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IPrintingV2 Interface](iprintingv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

