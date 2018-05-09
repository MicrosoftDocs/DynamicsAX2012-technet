---
title: IItemDataManager.GetItemsByBarcode Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetItemsByBarcode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IItemDataManager.GetItemsByBarcode(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.iitemdatamanager.getitemsbybarcode(v=AX.60)
ms:contentKeyID: 62212320
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IItemDataManager.GetItemsByBarcode
dev_langs:
- CSharp
- C++
- VB
---

# GetItemsByBarcode Method

Gets barcode information for the specified item barcode identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetItemsByBarcode ( _
    barcode As String, _
    columns As ColumnSet _
) As ItemBarcode
'Usage
Dim instance As IItemDataManager
Dim barcode As String
Dim columns As ColumnSet
Dim returnValue As ItemBarcode

returnValue = instance.GetItemsByBarcode(barcode, _
    columns)
```

``` csharp
ItemBarcode GetItemsByBarcode(
    string barcode,
    ColumnSet columns
)
```

``` c++
ItemBarcode^ GetItemsByBarcode(
    String^ barcode, 
    ColumnSet^ columns
)
```

#### Parameters

  - barcode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The item barcode information.  

## See Also

#### Reference

[IItemDataManager Interface](iitemdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

