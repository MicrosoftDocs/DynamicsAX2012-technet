---
title: IndiaTaxDataManager.GetReceiptHeaderTaxInfoIndia Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetReceiptHeaderTaxInfoIndia Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDataManager.GetReceiptHeaderTaxInfoIndia(Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.indiataxdatamanager.getreceiptheadertaxinfoindia(v=AX.60)
ms:contentKeyID: 62212266
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDataManager.GetReceiptHeaderTaxInfoIndia
dev_langs:
- CSharp
- C++
- VB
---

# GetReceiptHeaderTaxInfoIndia Method

Gets Receipt Header tax info.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetReceiptHeaderTaxInfoIndia ( _
    columns As ColumnSet _
) As ReceiptHeaderTaxInfoIndia
'Usage
Dim instance As IndiaTaxDataManager
Dim columns As ColumnSet
Dim returnValue As ReceiptHeaderTaxInfoIndia

returnValue = instance.GetReceiptHeaderTaxInfoIndia(columns)
```

``` csharp
public ReceiptHeaderTaxInfoIndia GetReceiptHeaderTaxInfoIndia(
    ColumnSet columns
)
```

``` c++
public:
ReceiptHeaderTaxInfoIndia^ GetReceiptHeaderTaxInfoIndia(
    ColumnSet^ columns
)
```

#### Parameters

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptHeaderTaxInfoIndia](receiptheadertaxinfoindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Receipt Header tax info.  

## See Also

#### Reference

[IndiaTaxDataManager Class](indiataxdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

