---
title: IPrinterV1.WindowsPrinting Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: WindowsPrinting Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrinterV1.WindowsPrinting(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprinterv1.windowsprinting(v=AX.60)
ms:contentKeyID: 47344328
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrinterV1.WindowsPrinting
dev_langs:
- CSharp
- C++
- VB
---

# WindowsPrinting Method

Prints text on the Windows Printer.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub WindowsPrinting ( _
    textToPrint As String, _
    printerName As String _
)
'Usage
Dim instance As IPrinterV1
Dim textToPrint As String
Dim printerName As String

instance.WindowsPrinting(textToPrint, _
    printerName)
```

``` csharp
void WindowsPrinting(
    string textToPrint,
    string printerName
)
```

``` c++
void WindowsPrinting(
    String^ textToPrint, 
    String^ printerName
)
```

#### Parameters

  - textToPrint  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - printerName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IPrinterV1 Interface](iprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

