---
title: ILogOnV1.LogOnOperator Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: LogOnOperator Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILogOnV1.LogOnOperator
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ilogonv1.logonoperator(v=AX.60)
ms:contentKeyID: 49836436
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILogOnV1.LogOnOperator
dev_langs:
- CSharp
- C++
- VB
---

# LogOnOperator Method

Initiate log on flow and returns the status.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function LogOnOperator As LogOnStatus
'Usage
Dim instance As ILogOnV1
Dim returnValue As LogOnStatus

returnValue = instance.LogOnOperator()
```

``` csharp
LogOnStatus LogOnOperator()
```

``` c++
LogOnStatus LogOnOperator()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.LogOnStatus](logonstatus-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
Log on status.  

## See Also

#### Reference

[ILogOnV1 Interface](ilogonv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

