---
title: ItemDataManager.IsProductOrVariantInCategory Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: IsProductOrVariantInCategory Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ItemDataManager.IsProductOrVariantInCategory(System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.itemdatamanager.isproductorvariantincategory(v=AX.60)
ms:contentKeyID: 62209972
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ItemDataManager.IsProductOrVariantInCategory
dev_langs:
- CSharp
- C++
- VB
---

# IsProductOrVariantInCategory Method

Checks whether the product or the variant is under the category.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function IsProductOrVariantInCategory ( _
    productRecordId As Long, _
    categoryRecordId As Long _
) As Boolean
'Usage
Dim instance As ItemDataManager
Dim productRecordId As Long
Dim categoryRecordId As Long
Dim returnValue As Boolean

returnValue = instance.IsProductOrVariantInCategory(productRecordId, _
    categoryRecordId)
```

``` csharp
public bool IsProductOrVariantInCategory(
    long productRecordId,
    long categoryRecordId
)
```

``` c++
public:
virtual bool IsProductOrVariantInCategory(
    long long productRecordId, 
    long long categoryRecordId
) sealed
```

#### Parameters

  - productRecordId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - categoryRecordId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
The check result.  

#### Implements

[IItemDataManager.IsProductOrVariantInCategory(Int64, Int64)](iitemdatamanager-isproductorvariantincategory-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ItemDataManager Class](itemdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

