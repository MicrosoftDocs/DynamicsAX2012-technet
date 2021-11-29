---
title: ICachedTaxDataManager.PutSalesTaxGroup Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutSalesTaxGroup Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedTaxDataManager.PutSalesTaxGroup(System.Collections.Generic.Dictionary{System.String,System.String},System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedtaxdatamanager.putsalestaxgroup(v=AX.60)
ms:contentKeyID: 62212678
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedTaxDataManager.PutSalesTaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# PutSalesTaxGroup Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales tax group for the given predicates.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutSalesTaxGroup ( _
    predicates As Dictionary(Of String, String), _
    result As String _
)
'Usage
Dim instance As ICachedTaxDataManager
Dim predicates As Dictionary(Of String, String)
Dim result As String

instance.PutSalesTaxGroup(predicates, _
    result)
```

``` csharp
void PutSalesTaxGroup(
    Dictionary<string, string> predicates,
    string result
)
```

``` c++
void PutSalesTaxGroup(
    Dictionary<String^, String^>^ predicates, 
    String^ result
)
```

#### Parameters

  - predicates  
    Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - result  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ICachedTaxDataManager Interface](icachedtaxdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

