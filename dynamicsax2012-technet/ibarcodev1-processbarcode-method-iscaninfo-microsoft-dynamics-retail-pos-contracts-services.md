---
title: IBarcodeV1.ProcessBarcode Method (IScanInfo) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ProcessBarcode Method (IScanInfo)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBarcodeV1.ProcessBarcode(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfo)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ibarcodev1.processbarcode(v=AX.60)
ms:contentKeyID: 47343943
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProcessBarcode Method (IScanInfo)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns an IBarcodeInfo object by using a given IScanInfo object.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ProcessBarcode ( _
    scanInfo As IScanInfo _
) As IBarcodeInfo
'Usage
Dim instance As IBarcodeV1
Dim scanInfo As IScanInfo
Dim returnValue As IBarcodeInfo

returnValue = instance.ProcessBarcode(scanInfo)
```

``` csharp
IBarcodeInfo ProcessBarcode(
    IScanInfo scanInfo
)
```

``` c++
IBarcodeInfo^ ProcessBarcode(
    IScanInfo^ scanInfo
)
```

#### Parameters

  - scanInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfo](iscaninfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfo](ibarcodeinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The bar code information.  

## See Also

#### Reference

[IBarcodeV1 Interface](ibarcodev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[ProcessBarcode Overload](ibarcodev1-processbarcode-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

