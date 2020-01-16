---
title: CustomClaimsProvider.Name Property  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: Name Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.Name
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.customclaimsprovider.name(v=AX.60)
ms:contentKeyID: 62207696
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.CustomClaimsProvider.Name
dev_langs:
- CSharp
- C++
- VB
---

# Name Property

Gets the name.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Common (in Microsoft.Dynamics.Retail.SP.Web.Common.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property Name As String
    Get
'Usage
Dim instance As CustomClaimsProvider
Dim value As String

value = instance.Name
```

``` csharp
public override string Name { get; }
```

``` c++
public:
virtual property String^ Name {
    String^ get () override;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The name.  

## See Also

#### Reference

[CustomClaimsProvider Class](customclaimsprovider-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

