---
title: ICachedItemDataManager.PutItemsByBarcode Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutItemsByBarcode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedItemDataManager.PutItemsByBarcode(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.icacheditemdatamanager.putitemsbybarcode(v=AX.60)
ms:contentKeyID: 62214539
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedItemDataManager.PutItemsByBarcode
dev_langs:
- CSharp
- C++
- VB
---

# PutItemsByBarcode Method

Stores barcode information for the specified item barcode identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutItemsByBarcode ( _
    barcode As String, _
    columns As ColumnSet, _
    result As ItemBarcode _
)
'Usage
Dim instance As ICachedItemDataManager
Dim barcode As String
Dim columns As ColumnSet
Dim result As ItemBarcode

instance.PutItemsByBarcode(barcode, columns, _
    result)
```

``` csharp
void PutItemsByBarcode(
    string barcode,
    ColumnSet columns,
    ItemBarcode result
)
```

``` c++
void PutItemsByBarcode(
    String^ barcode, 
    ColumnSet^ columns, 
    ItemBarcode^ result
)
```

#### Parameters

  - barcode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columns  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedItemDataManager Interface](icacheditemdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

