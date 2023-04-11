---
title: ExtendedWebAppWebConfigActivationJob Class (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: ExtendedWebAppWebConfigActivationJob Class
ms:assetid: T:Microsoft.Dynamics.Retail.SP.CommonFeatures.ExtendedWebAppWebConfigActivationJob
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.extendedwebappwebconfigactivationjob(v=AX.60)
ms:contentKeyID: 62202868
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.ExtendedWebAppWebConfigActivationJob
dev_langs:
- CSharp
- C++
- VB
---

# ExtendedWebAppWebConfigActivationJob Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Class for job that carries out the activation steps for the extended web app settings in the STS web.config.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class ExtendedWebAppWebConfigActivationJob _
    Inherits ExtendedWebAppWebConfigUpdatingJob
'Usage
Dim instance As ExtendedWebAppWebConfigActivationJob
```

``` csharp
public sealed class ExtendedWebAppWebConfigActivationJob : ExtendedWebAppWebConfigUpdatingJob
```

``` c++
public ref class ExtendedWebAppWebConfigActivationJob sealed : public ExtendedWebAppWebConfigUpdatingJob
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  SPAutoSerializingObject  
    SPPersistedObject  
      SPJobDefinition  
        [Microsoft.Dynamics.Retail.SP.CommonFeatures.ExtendedWebAppWebConfigUpdatingJob](extendedwebappwebconfigupdatingjob-class-microsoft-dynamics-retail-sp-commonfeatures.md)  
          Microsoft.Dynamics.Retail.SP.CommonFeatures.ExtendedWebAppWebConfigActivationJob  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

