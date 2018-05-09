---
title: ICachedItemDataManager.PutVariantByVariantId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutVariantByVariantId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedItemDataManager.PutVariantByVariantId(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.icacheditemdatamanager.putvariantbyvariantid(v=AX.60)
ms:contentKeyID: 62206399
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedItemDataManager.PutVariantByVariantId
dev_langs:
- CSharp
- C++
- VB
---

# PutVariantByVariantId Method

Stores the variant using the specified variant identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutVariantByVariantId ( _
    variantId As String, _
    columnSet As ColumnSet, _
    result As ProductVariant _
)
'Usage
Dim instance As ICachedItemDataManager
Dim variantId As String
Dim columnSet As ColumnSet
Dim result As ProductVariant

instance.PutVariantByVariantId(variantId, _
    columnSet, result)
```

``` csharp
void PutVariantByVariantId(
    string variantId,
    ColumnSet columnSet,
    ProductVariant result
)
```

``` c++
void PutVariantByVariantId(
    String^ variantId, 
    ColumnSet^ columnSet, 
    ProductVariant^ result
)
```

#### Parameters

  - variantId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedItemDataManager Interface](icacheditemdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

