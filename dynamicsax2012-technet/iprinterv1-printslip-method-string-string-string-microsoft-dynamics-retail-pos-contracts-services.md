---
title: IPrinterV1.PrintSlip Method (String, String, String) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintSlip Method (String, String, String)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrinterV1.PrintSlip(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprinterv1.printslip(v=AX.60)
ms:contentKeyID: 47344145
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PrintSlip Method (String, String, String)

Prints text on the OPOS printer as slip.

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
Dim instance As IPrinterV1
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

[IPrinterV1 Interface](iprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[PrintSlip Overload](iprinterv1-printslip-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

