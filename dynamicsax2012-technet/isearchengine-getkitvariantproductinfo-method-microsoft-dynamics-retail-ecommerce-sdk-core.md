---
title: ISearchEngine.GetKitVariantProductInfo Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core)
TOCTitle: GetKitVariantProductInfo Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine.GetKitVariantProductInfo(System.Int64,System.Int64,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineProductProperty})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.isearchengine.getkitvariantproductinfo(v=AX.60)
ms:contentKeyID: 65315644
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine.GetKitVariantProductInfo
dev_langs:
- CSharp
- C++
- VB
---

# GetKitVariantProductInfo Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Function GetKitVariantProductInfo ( _
    kitMasterProductId As Long, _
    catalogId As Long, _
    kitLines As IEnumerable(Of KitLineProductProperty) _
) As Tuple(Of String, String, Long, String)
'Usage
Dim instance As ISearchEngine
Dim kitMasterProductId As Long
Dim catalogId As Long
Dim kitLines As IEnumerable(Of KitLineProductProperty)
Dim returnValue As Tuple(Of String, String, Long, String)

returnValue = instance.GetKitVariantProductInfo(kitMasterProductId, _
    catalogId, kitLines)
```

``` csharp
Tuple<string, string, long, string> GetKitVariantProductInfo(
    long kitMasterProductId,
    long catalogId,
    IEnumerable<KitLineProductProperty> kitLines
)
```

``` c++
Tuple<String^, String^, long long, String^>^ GetKitVariantProductInfo(
    long long kitMasterProductId, 
    long long catalogId, 
    IEnumerable<KitLineProductProperty^>^ kitLines
)
```

#### Parameters

  - kitMasterProductId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - kitLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<KitLineProductProperty\>  

#### Return Value

Type: Tuple\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[ISearchEngine Interface](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)

