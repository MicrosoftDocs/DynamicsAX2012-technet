---
title: IFiscalPrinterV1.PrintSlip Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintSlip Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PrintSlip(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.printslip(v=AX.60)
ms:contentKeyID: 62205599
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PrintSlip
dev_langs:
- CSharp
- C++
- VB
---

# PrintSlip Method

Prints a slip containing the text in the textToPrint parameter

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintSlip ( _
    header As String, _
    details As String, _
    footer As String _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim header As String
Dim details As String
Dim footer As String

instance.PrintSlip(header, details, footer)
```

``` csharp
void PrintSlip(
    string header,
    string details,
    string footer
)
```

``` c++
void PrintSlip(
    String^ header, 
    String^ details, 
    String^ footer
)
```

#### Parameters

  - header  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - details  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - footer  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

