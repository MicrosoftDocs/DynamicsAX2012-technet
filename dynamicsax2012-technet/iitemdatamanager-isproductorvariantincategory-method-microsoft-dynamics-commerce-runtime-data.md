---
title: IItemDataManager.IsProductOrVariantInCategory Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: IsProductOrVariantInCategory Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IItemDataManager.IsProductOrVariantInCategory(System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.iitemdatamanager.isproductorvariantincategory(v=AX.60)
ms:contentKeyID: 62213316
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IItemDataManager.IsProductOrVariantInCategory
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
Function IsProductOrVariantInCategory ( _
    productRecordId As Long, _
    categoryRecordId As Long _
) As Boolean
'Usage
Dim instance As IItemDataManager
Dim productRecordId As Long
Dim categoryRecordId As Long
Dim returnValue As Boolean

returnValue = instance.IsProductOrVariantInCategory(productRecordId, _
    categoryRecordId)
```

``` csharp
bool IsProductOrVariantInCategory(
    long productRecordId,
    long categoryRecordId
)
```

``` c++
bool IsProductOrVariantInCategory(
    long long productRecordId, 
    long long categoryRecordId
)
```

#### Parameters

  - productRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - categoryRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The check result.  

## See Also

#### Reference

[IItemDataManager Interface](iitemdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

