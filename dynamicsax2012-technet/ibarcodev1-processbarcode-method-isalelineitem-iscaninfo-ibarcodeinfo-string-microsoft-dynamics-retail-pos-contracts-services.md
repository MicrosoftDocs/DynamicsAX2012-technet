---
title: IBarcodeV1.ProcessBarcode Method (ISaleLineItem, IScanInfo, IBarcodeInfo, String) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ProcessBarcode Method (ISaleLineItem, IScanInfo, IBarcodeInfo, String)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBarcodeV1.ProcessBarcode(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfo,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfo,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ibarcodev1.processbarcode(v=AX.60)
ms:contentKeyID: 47344304
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProcessBarcode Method (ISaleLineItem, IScanInfo, IBarcodeInfo, String)

Returns an IBarcodeInfo object by using four parameters.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ProcessBarcode ( _
    saleLineItem As ISaleLineItem, _
    scanInfo As IScanInfo, _
    barcodeInfo As IBarcodeInfo, _
    barcode As String _
) As IBarcodeInfo
'Usage
Dim instance As IBarcodeV1
Dim saleLineItem As ISaleLineItem
Dim scanInfo As IScanInfo
Dim barcodeInfo As IBarcodeInfo
Dim barcode As String
Dim returnValue As IBarcodeInfo

returnValue = instance.ProcessBarcode(saleLineItem, _
    scanInfo, barcodeInfo, barcode)
```

``` csharp
IBarcodeInfo ProcessBarcode(
    ISaleLineItem saleLineItem,
    IScanInfo scanInfo,
    IBarcodeInfo barcodeInfo,
    string barcode
)
```

``` c++
IBarcodeInfo^ ProcessBarcode(
    ISaleLineItem^ saleLineItem, 
    IScanInfo^ scanInfo, 
    IBarcodeInfo^ barcodeInfo, 
    String^ barcode
)
```

#### Parameters

  - saleLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - scanInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IScanInfo](iscaninfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - barcodeInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfo](ibarcodeinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - barcode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfo](ibarcodeinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The bar code information as an IBarcodeInfo object.  

## See Also

[IBarcodeV1 Interface](ibarcodev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[ProcessBarcode Overload](ibarcodev1-processbarcode-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

[IBarcodeInfo](ibarcodeinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

