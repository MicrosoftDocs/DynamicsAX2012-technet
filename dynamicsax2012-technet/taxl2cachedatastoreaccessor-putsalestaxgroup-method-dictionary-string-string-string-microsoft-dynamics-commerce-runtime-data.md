---
title: TaxL2CacheDataStoreAccessor.PutSalesTaxGroup Method (Dictionary(String, String), String) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutSalesTaxGroup Method (Dictionary(String, String), String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.PutSalesTaxGroup(System.Collections.Generic.Dictionary{System.String,System.String},System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.putsalestaxgroup(v=AX.60)
ms:contentKeyID: 62208699
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PutSalesTaxGroup Method (Dictionary(String, String), String)

Gets the sales tax group for the given predicates.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutSalesTaxGroup ( _
    predicates As Dictionary(Of String, String), _
    result As String _
)
'Usage
Dim instance As TaxL2CacheDataStoreAccessor
Dim predicates As Dictionary(Of String, String)
Dim result As String

instance.PutSalesTaxGroup(predicates, _
    result)
```

``` csharp
public void PutSalesTaxGroup(
    Dictionary<string, string> predicates,
    string result
)
```

``` c++
public:
virtual void PutSalesTaxGroup(
    Dictionary<String^, String^>^ predicates, 
    String^ result
) sealed
```

#### Parameters

  - predicates  
    Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/en-us/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - result  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Implements

[ICachedTaxDataManager.PutSalesTaxGroup(Dictionary\<String, String\>, String)](icachedtaxdatamanager-putsalestaxgroup-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[PutSalesTaxGroup Overload](taxl2cachedatastoreaccessor-putsalestaxgroup-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

