---
title: IFiscalPrinterV1.CapStatus Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CapStatus Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.CapStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.capstatus(v=AX.60)
ms:contentKeyID: 62203933
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.CapStatus
dev_langs:
- CSharp
- C++
- VB
---

# CapStatus Method

Check if the cash drawer is capable of reporting back whether it's closed or open.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CapStatus As Boolean
'Usage
Dim instance As IFiscalPrinterV1
Dim returnValue As Boolean

returnValue = instance.CapStatus()
```

``` csharp
bool CapStatus()
```

``` c++
bool CapStatus()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if capable, false otherwise.  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

