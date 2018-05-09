---
title: UrlRewriteWebConfigUpdater Constructor  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: UrlRewriteWebConfigUpdater Constructor
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.UrlRewriteWebConfigUpdater.#ctor(System.String,System.Collections.Generic.IEnumerable{System.String},System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.urlrewritewebconfigupdater.urlrewritewebconfigupdater(v=AX.60)
ms:contentKeyID: 62204869
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.UrlRewriteWebConfigUpdater.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UrlRewriteWebConfigUpdater Constructor

Initializes a new instance of the [UrlRewriteWebConfigUpdater](urlrewritewebconfigupdater-class-microsoft-dynamics-retail-sp-commonfeatures.md) class.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    rewriteRulesPrefix As String, _
    secureResources As IEnumerable(Of String), _
    supportingFileExtensions As IEnumerable(Of String) _
)
'Usage
Dim rewriteRulesPrefix As String
Dim secureResources As IEnumerable(Of String)
Dim supportingFileExtensions As IEnumerable(Of String)

Dim instance As New UrlRewriteWebConfigUpdater(rewriteRulesPrefix, _
    secureResources, supportingFileExtensions)
```

``` csharp
public UrlRewriteWebConfigUpdater(
    string rewriteRulesPrefix,
    IEnumerable<string> secureResources,
    IEnumerable<string> supportingFileExtensions
)
```

``` c++
public:
UrlRewriteWebConfigUpdater(
    String^ rewriteRulesPrefix, 
    IEnumerable<String^>^ secureResources, 
    IEnumerable<String^>^ supportingFileExtensions
)
```

#### Parameters

  - rewriteRulesPrefix  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - secureResources  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - supportingFileExtensions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[UrlRewriteWebConfigUpdater Class](urlrewritewebconfigupdater-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

