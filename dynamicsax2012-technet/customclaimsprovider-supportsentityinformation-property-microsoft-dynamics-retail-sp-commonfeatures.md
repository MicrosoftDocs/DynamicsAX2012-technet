---
title: CustomClaimsProvider.SupportsEntityInformation Property  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: SupportsEntityInformation Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.SupportsEntityInformation
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.customclaimsprovider.supportsentityinformation(v=AX.60)
ms:contentKeyID: 62202639
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.SupportsEntityInformation
dev_langs:
- CSharp
- C++
- VB
---

# SupportsEntityInformation Property

Gets a value indicating whether \[supports entity information\].

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property SupportsEntityInformation As Boolean
    Get
'Usage
Dim instance As CustomClaimsProvider
Dim value As Boolean

value = instance.SupportsEntityInformation
```

``` csharp
public override bool SupportsEntityInformation { get; }
```

``` c++
public:
virtual property bool SupportsEntityInformation {
    bool get () override;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true if \[supports entity information\]; otherwise, false.  

## See Also

#### Reference

[CustomClaimsProvider Class](customclaimsprovider-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

