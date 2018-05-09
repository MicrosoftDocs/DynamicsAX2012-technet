---
title: ItemDataManager.GetItemsByBarcode Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetItemsByBarcode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ItemDataManager.GetItemsByBarcode(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.itemdatamanager.getitemsbybarcode(v=AX.60)
ms:contentKeyID: 62213506
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ItemDataManager.GetItemsByBarcode
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
Public Function GetItemsByBarcode ( _
    barcode As String, _
    columns As ColumnSet _
) As ItemBarcode
'Usage
Dim instance As ItemDataManager
Dim barcode As String
Dim columns As ColumnSet
Dim returnValue As ItemBarcode

returnValue = instance.GetItemsByBarcode(barcode, _
    columns)
```

``` csharp
public ItemBarcode GetItemsByBarcode(
    string barcode,
    ColumnSet columns
)
```

``` c++
public:
virtual ItemBarcode^ GetItemsByBarcode(
    String^ barcode, 
    ColumnSet^ columns
) sealed
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

#### Implements

[IItemDataManager.GetItemsByBarcode(String, ColumnSet)](iitemdatamanager-getitemsbybarcode-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ItemDataManager Class](itemdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

