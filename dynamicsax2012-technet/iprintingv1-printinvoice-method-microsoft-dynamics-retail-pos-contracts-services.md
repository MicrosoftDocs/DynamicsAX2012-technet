---
title: IPrintingV1.PrintInvoice Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintInvoice Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintInvoice(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iprintingv1.printinvoice(v=AX.60)
ms:contentKeyID: 47343848
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.PrintInvoice
dev_langs:
- CSharp
- C++
- VB
---

# PrintInvoice Method

Prints the invoice.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function PrintInvoice ( _
    posTransaction As IPosTransaction, _
    copyInvoice As Boolean, _
    printPreview As Boolean _
) As Boolean
'Usage
Dim instance As IPrintingV1
Dim posTransaction As IPosTransaction
Dim copyInvoice As Boolean
Dim printPreview As Boolean
Dim returnValue As Boolean

returnValue = instance.PrintInvoice(posTransaction, _
    copyInvoice, printPreview)
```

``` csharp
bool PrintInvoice(
    IPosTransaction posTransaction,
    bool copyInvoice,
    bool printPreview
)
```

``` c++
bool PrintInvoice(
    IPosTransaction^ posTransaction, 
    bool copyInvoice, 
    bool printPreview
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - copyInvoice  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - printPreview  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true if printed; otherwise, false.  

## See Also

#### Reference

[IPrintingV1 Interface](iprintingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

