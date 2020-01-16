---
title: IRFIDV1.GetUnProcessedRFIDs Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetUnProcessedRFIDs Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRFIDV1.GetUnProcessedRFIDs
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.irfidv1.getunprocessedrfids(v=AX.60)
ms:contentKeyID: 47344023
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRFIDV1.GetUnProcessedRFIDs
dev_langs:
- CSharp
- C++
- VB
---

# GetUnProcessedRFIDs Method

Gets unprocessed RFIDs.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetUnProcessedRFIDs As IScanInfo()
'Usage
Dim instance As IRFIDV1
Dim returnValue As IScanInfo()

returnValue = instance.GetUnProcessedRFIDs()
```

``` csharp
IScanInfo[] GetUnProcessedRFIDs()
```

``` c++
array<IScanInfo^>^ GetUnProcessedRFIDs()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfo](iscaninfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\[\]  
The newly scanned items by RFID device that Retail POS must add to the sale.  

## See Also

#### Reference

[IRFIDV1 Interface](irfidv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

