---
title: CustomClaimsProvider.SupportsResolve Property  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: SupportsResolve Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.SupportsResolve
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.customclaimsprovider.supportsresolve(v=AX.60)
ms:contentKeyID: 62206764
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.SupportsResolve
dev_langs:
- CSharp
- C++
- VB
---

# SupportsResolve Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether \[supports resolve\].

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property SupportsResolve As Boolean
    Get
'Usage
Dim instance As CustomClaimsProvider
Dim value As Boolean

value = instance.SupportsResolve
```

``` csharp
public override bool SupportsResolve { get; }
```

``` c++
public:
virtual property bool SupportsResolve {
    bool get () override;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if \[supports resolve\]; otherwise, false.  

## See Also

#### Reference

[CustomClaimsProvider Class](customclaimsprovider-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

