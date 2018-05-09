---
title: IPrintingV3.PrintExternalReceipt Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintExternalReceipt Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV3.PrintExternalReceipt(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iprintingv3.printexternalreceipt(v=AX.60)
ms:contentKeyID: 62204524
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV3.PrintExternalReceipt
dev_langs:
- CSharp
- C++
- VB
---

# PrintExternalReceipt Method

Prints external receipt, i.e., any document received from an external device or a service.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintExternalReceipt ( _
    text As String _
)
'Usage
Dim instance As IPrintingV3
Dim text As String

instance.PrintExternalReceipt(text)
```

``` csharp
void PrintExternalReceipt(
    string text
)
```

``` c++
void PrintExternalReceipt(
    String^ text
)
```

#### Parameters

  - text  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## Remarks

This method is used for printing external receipts, i.e., any documents received from some external devices or services.

This kind of documents may require some special uniform handling, such as applying special rules for choosing a peripheral device for printing, etc.

## See Also

#### Reference

[IPrintingV3 Interface](iprintingv3-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

