---
title: CustomClaimsProvider.SupportsHierarchy Property  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: SupportsHierarchy Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.SupportsHierarchy
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.customclaimsprovider.supportshierarchy(v=AX.60)
ms:contentKeyID: 62204796
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.SupportsHierarchy
dev_langs:
- CSharp
- C++
- VB
---

# SupportsHierarchy Property

Gets a value indicating whether \[supports hierarchy\].

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property SupportsHierarchy As Boolean
    Get
'Usage
Dim instance As CustomClaimsProvider
Dim value As Boolean

value = instance.SupportsHierarchy
```

``` csharp
public override bool SupportsHierarchy { get; }
```

``` c++
public:
virtual property bool SupportsHierarchy {
    bool get () override;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if \[supports hierarchy\]; otherwise, false.  

## See Also

#### Reference

[CustomClaimsProvider Class](customclaimsprovider-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

