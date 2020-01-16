---
title: ProductManager.GetBarcode Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetBarcode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetBarcode(Microsoft.Dynamics.Commerce.Runtime.DataModel.ScanInfo,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.getbarcode(v=AX.60)
ms:contentKeyID: 65317882
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetBarcode
dev_langs:
- CSharp
- C++
- VB
---

# GetBarcode Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetBarcode ( _
    scanInfo As ScanInfo, _
    settings As QueryResultSettings _
) As Barcode
'Usage
Dim instance As ProductManager
Dim scanInfo As ScanInfo
Dim settings As QueryResultSettings
Dim returnValue As Barcode

returnValue = instance.GetBarcode(scanInfo, _
    settings)
```

``` csharp
public Barcode GetBarcode(
    ScanInfo scanInfo,
    QueryResultSettings settings
)
```

``` c++
public:
Barcode^ GetBarcode(
    ScanInfo^ scanInfo, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - scanInfo  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ScanInfo](scaninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

