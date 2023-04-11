---
title: CustomClaimsProvider.SupportsSearch Property  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: SupportsSearch Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.SupportsSearch
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.customclaimsprovider.supportssearch(v=AX.60)
ms:contentKeyID: 62203283
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.SupportsSearch
dev_langs:
- CSharp
- C++
- VB
---

# SupportsSearch Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether \[supports search\].

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property SupportsSearch As Boolean
    Get
'Usage
Dim instance As CustomClaimsProvider
Dim value As Boolean

value = instance.SupportsSearch
```

``` csharp
public override bool SupportsSearch { get; }
```

``` c++
public:
virtual property bool SupportsSearch {
    bool get () override;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if \[supports search\]; otherwise, false.  

## See Also

#### Reference

[CustomClaimsProvider Class](customclaimsprovider-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

