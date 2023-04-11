---
title: ISearchEngine.GetKitComponentVariants Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core)
TOCTitle: GetKitComponentVariants Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine.GetKitComponentVariants(System.Int64,System.Int64,System.Int64,System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.isearchengine.getkitcomponentvariants(v=AX.60)
ms:contentKeyID: 65318749
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine.GetKitComponentVariants
dev_langs:
- CSharp
- C++
- VB
---

# GetKitComponentVariants Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Function GetKitComponentVariants ( _
    kitComponentProductId As Long, _
    kitComponentParentId As Long, _
    parentKitId As Long, _
    kitComponentLineId As Long, _
    catalogId As Long _
) As IEnumerable(Of StorefrontListItem)
'Usage
Dim instance As ISearchEngine
Dim kitComponentProductId As Long
Dim kitComponentParentId As Long
Dim parentKitId As Long
Dim kitComponentLineId As Long
Dim catalogId As Long
Dim returnValue As IEnumerable(Of StorefrontListItem)

returnValue = instance.GetKitComponentVariants(kitComponentProductId, _
    kitComponentParentId, parentKitId, _
    kitComponentLineId, catalogId)
```

``` csharp
IEnumerable<StorefrontListItem> GetKitComponentVariants(
    long kitComponentProductId,
    long kitComponentParentId,
    long parentKitId,
    long kitComponentLineId,
    long catalogId
)
```

``` c++
IEnumerable<StorefrontListItem^>^ GetKitComponentVariants(
    long long kitComponentProductId, 
    long long kitComponentParentId, 
    long long parentKitId, 
    long long kitComponentLineId, 
    long long catalogId
)
```

#### Parameters

  - kitComponentProductId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitComponentParentId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - parentKitId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitComponentLineId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StorefrontListItem](storefrontlistitem-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[ISearchEngine Interface](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)

