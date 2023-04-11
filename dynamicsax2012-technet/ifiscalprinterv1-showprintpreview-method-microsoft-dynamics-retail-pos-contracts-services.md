---
title: IFiscalPrinterV1.ShowPrintPreview Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ShowPrintPreview Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.ShowPrintPreview(Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.showprintpreview(v=AX.60)
ms:contentKeyID: 62203107
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.ShowPrintPreview
dev_langs:
- CSharp
- C++
- VB
---

# ShowPrintPreview Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns true if print preview ids shown.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ShowPrintPreview ( _
    formType As FormType, _
    posTransaction As IPosTransaction _
) As Boolean
'Usage
Dim instance As IFiscalPrinterV1
Dim formType As FormType
Dim posTransaction As IPosTransaction
Dim returnValue As Boolean

returnValue = instance.ShowPrintPreview(formType, _
    posTransaction)
```

``` csharp
bool ShowPrintPreview(
    FormType formType,
    IPosTransaction posTransaction
)
```

``` c++
bool ShowPrintPreview(
    FormType formType, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - formType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType](formtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

