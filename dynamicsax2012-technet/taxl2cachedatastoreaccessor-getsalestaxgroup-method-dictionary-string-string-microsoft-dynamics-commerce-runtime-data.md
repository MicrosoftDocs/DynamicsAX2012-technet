---
title: TaxL2CacheDataStoreAccessor.GetSalesTaxGroup Method (Dictionary(String, String)) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetSalesTaxGroup Method (Dictionary(String, String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.GetSalesTaxGroup(System.Collections.Generic.Dictionary{System.String,System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.getsalestaxgroup(v=AX.60)
ms:contentKeyID: 62205153
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetSalesTaxGroup Method (Dictionary(String, String))

Gets the sales tax group for the given predicates.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetSalesTaxGroup ( _
    predicates As Dictionary(Of String, String) _
) As String
'Usage
Dim instance As TaxL2CacheDataStoreAccessor
Dim predicates As Dictionary(Of String, String)
Dim returnValue As String

returnValue = instance.GetSalesTaxGroup(predicates)
```

``` csharp
public string GetSalesTaxGroup(
    Dictionary<string, string> predicates
)
```

``` c++
public:
String^ GetSalesTaxGroup(
    Dictionary<String^, String^>^ predicates
)
```

#### Parameters

  - predicates  
    Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/en-us/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
A single tax group if found; otherwise, NULL.  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[GetSalesTaxGroup Overload](taxl2cachedatastoreaccessor-getsalestaxgroup-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

