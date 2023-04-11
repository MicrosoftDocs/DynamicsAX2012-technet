---
title: IPrinterV1.PrintReceipt Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintReceipt Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrinterV1.PrintReceipt(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprinterv1.printreceipt(v=AX.60)
ms:contentKeyID: 47344415
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrinterV1.PrintReceipt
dev_langs:
- CSharp
- C++
- VB
---

# PrintReceipt Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Prints text on the OPOS printer.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintReceipt ( _
    text As String _
)
'Usage
Dim instance As IPrinterV1
Dim text As String

instance.PrintReceipt(text)
```

``` csharp
void PrintReceipt(
    string text
)
```

``` c++
void PrintReceipt(
    String^ text
)
```

#### Parameters

  - text  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IPrinterV1 Interface](iprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

