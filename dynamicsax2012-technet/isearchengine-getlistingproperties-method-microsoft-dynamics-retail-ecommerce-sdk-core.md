---
title: ISearchEngine.GetListingProperties Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core)
TOCTitle: GetListingProperties Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine.GetListingProperties(System.Boolean,System.Int64,System.String[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.isearchengine.getlistingproperties(v=AX.60)
ms:contentKeyID: 65317774
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine.GetListingProperties
dev_langs:
- CSharp
- C++
- VB
---

# GetListingProperties Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Function GetListingProperties ( _
    isResultMandatory As Boolean, _
    listingRecordId As Long, _
    ParamArray propertyNames As String() _
) As IDictionary(Of String, Object)
'Usage
Dim instance As ISearchEngine
Dim isResultMandatory As Boolean
Dim listingRecordId As Long
Dim propertyNames As String()
Dim returnValue As IDictionary(Of String, Object)

returnValue = instance.GetListingProperties(isResultMandatory, _
    listingRecordId, propertyNames)
```

``` csharp
IDictionary<string, Object> GetListingProperties(
    bool isResultMandatory,
    long listingRecordId,
    params string[] propertyNames
)
```

``` c++
IDictionary<String^, Object^>^ GetListingProperties(
    bool isResultMandatory, 
    long long listingRecordId, 
    ... array<String^>^ propertyNames
)
```

#### Parameters

  - isResultMandatory  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - listingRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - propertyNames  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

#### Return Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>  

## See Also

#### Reference

[ISearchEngine Interface](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)

