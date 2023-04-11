---
title: DataCacheAccessor.CalculateVariantHash Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CalculateVariantHash Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.CalculateVariantHash(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datacacheaccessor.calculatevarianthash(v=AX.60)
ms:contentKeyID: 65315904
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataCacheAccessor.CalculateVariantHash
dev_langs:
- CSharp
- C++
- VB
---

# CalculateVariantHash Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Calculates the hash of a given variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function CalculateVariantHash ( _
    variant As ProductVariant _
) As Integer
'Usage
Dim variant As ProductVariant
Dim returnValue As Integer

returnValue = DataCacheAccessor.CalculateVariantHash(variant)
```

``` csharp
protected static int CalculateVariantHash(
    ProductVariant variant
)
```

``` c++
protected:
static int CalculateVariantHash(
    ProductVariant^ variant
)
```

#### Parameters

  - variant  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Hash corresponding to this variant object.  

## See Also

#### Reference

[DataCacheAccessor Class](datacacheaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

