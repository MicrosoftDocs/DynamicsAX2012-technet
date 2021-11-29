---
title: ISearchEngine.GetListingsProperties Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core)
TOCTitle: GetListingsProperties Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine.GetListingsProperties(System.Boolean,System.Collections.Generic.IEnumerable{System.Int64},System.String[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.isearchengine.getlistingsproperties(v=AX.60)
ms:contentKeyID: 65317631
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine.GetListingsProperties
dev_langs:
- CSharp
- C++
- VB
---

# GetListingsProperties Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Function GetListingsProperties ( _
    isResultMandatory As Boolean, _
    listingRecordIds As IEnumerable(Of Long), _
    ParamArray propertyNames As String() _
) As IDictionary(Of Long, IDictionary(Of String, Object))
'Usage
Dim instance As ISearchEngine
Dim isResultMandatory As Boolean
Dim listingRecordIds As IEnumerable(Of Long)
Dim propertyNames As String()
Dim returnValue As IDictionary(Of Long, IDictionary(Of String, Object))

returnValue = instance.GetListingsProperties(isResultMandatory, _
    listingRecordIds, propertyNames)
```

``` csharp
IDictionary<long, IDictionary<string, Object>> GetListingsProperties(
    bool isResultMandatory,
    IEnumerable<long> listingRecordIds,
    params string[] propertyNames
)
```

``` c++
IDictionary<long long, IDictionary<String^, Object^>^>^ GetListingsProperties(
    bool isResultMandatory, 
    IEnumerable<long long>^ listingRecordIds, 
    ... array<String^>^ propertyNames
)
```

#### Parameters

  - isResultMandatory  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - listingRecordIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - propertyNames  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

#### Return Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>\>  

## See Also

#### Reference

[ISearchEngine Interface](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)

