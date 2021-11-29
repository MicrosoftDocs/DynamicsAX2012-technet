---
title: STSFormBasedAuthWebConfigUpdatingJob.IsForActivation Property  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: IsForActivation Property
ms:assetid: P:Microsoft.Dynamics.Retail.SP.CommonFeatures.STSFormBasedAuthWebConfigUpdatingJob.IsForActivation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.stsformbasedauthwebconfigupdatingjob.isforactivation(v=AX.60)
ms:contentKeyID: 62205616
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.STSFormBasedAuthWebConfigUpdatingJob.IsForActivation
dev_langs:
- CSharp
- C++
- VB
---

# IsForActivation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the value indicating whether this job is for activation or deactivation.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Protected MustOverride ReadOnly Property IsForActivation As Boolean
    Get
'Usage
Dim value As Boolean

value = Me.IsForActivation
```

``` csharp
protected abstract bool IsForActivation { get; }
```

``` c++
protected:
virtual property bool IsForActivation {
    bool get () abstract;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[STSFormBasedAuthWebConfigUpdatingJob Class](stsformbasedauthwebconfigupdatingjob-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

