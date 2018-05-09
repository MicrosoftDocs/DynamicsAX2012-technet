---
title: IBarcodeV1.ProcessBarcode Method (BarcodeEntryType, String) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ProcessBarcode Method (BarcodeEntryType, String)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBarcodeV1.ProcessBarcode(Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeEntryType,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ibarcodev1.processbarcode(v=AX.60)
ms:contentKeyID: 47344057
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProcessBarcode Method (BarcodeEntryType, String)

Returns an IBarcodeInfo object by using a string and a BarcodeEntryType object.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ProcessBarcode ( _
    barcodeEntrytype As BarcodeEntryType, _
    barcode As String _
) As IBarcodeInfo
'Usage
Dim instance As IBarcodeV1
Dim barcodeEntrytype As BarcodeEntryType
Dim barcode As String
Dim returnValue As IBarcodeInfo

returnValue = instance.ProcessBarcode(barcodeEntrytype, _
    barcode)
```

``` csharp
IBarcodeInfo ProcessBarcode(
    BarcodeEntryType barcodeEntrytype,
    string barcode
)
```

``` c++
IBarcodeInfo^ ProcessBarcode(
    BarcodeEntryType barcodeEntrytype, 
    String^ barcode
)
```

#### Parameters

  - barcodeEntrytype  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.BarcodeEntryType](barcodeentrytype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - barcode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBarcodeInfo](ibarcodeinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The bar code information.  

## See Also

#### Reference

[IBarcodeV1 Interface](ibarcodev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[ProcessBarcode Overload](ibarcodev1-processbarcode-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

