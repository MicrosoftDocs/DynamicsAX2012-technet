---
title: IPrintingV1.ShowPrintPreview Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ShowPrintPreview Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.ShowPrintPreview(Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iprintingv1.showprintpreview(v=AX.60)
ms:contentKeyID: 62202340
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrintingV1.ShowPrintPreview
dev_langs:
- CSharp
- C++
- VB
---

# ShowPrintPreview Method

show preview

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ShowPrintPreview ( _
    formType As FormType, _
    posTransaction As IPosTransaction, _
    saleItem As ISaleLineItem _
) As Boolean
'Usage
Dim instance As IPrintingV1
Dim formType As FormType
Dim posTransaction As IPosTransaction
Dim saleItem As ISaleLineItem
Dim returnValue As Boolean

returnValue = instance.ShowPrintPreview(formType, _
    posTransaction, saleItem)
```

``` csharp
bool ShowPrintPreview(
    FormType formType,
    IPosTransaction posTransaction,
    ISaleLineItem saleItem
)
```

``` c++
bool ShowPrintPreview(
    FormType formType, 
    IPosTransaction^ posTransaction, 
    ISaleLineItem^ saleItem
)
```

#### Parameters

  - formType  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType](formtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - saleItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IPrintingV1 Interface](iprintingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

