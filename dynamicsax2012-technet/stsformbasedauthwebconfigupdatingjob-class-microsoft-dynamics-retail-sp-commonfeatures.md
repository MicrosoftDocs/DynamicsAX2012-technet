---
title: STSFormBasedAuthWebConfigUpdatingJob Class (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: STSFormBasedAuthWebConfigUpdatingJob Class
ms:assetid: T:Microsoft.Dynamics.Retail.SP.CommonFeatures.STSFormBasedAuthWebConfigUpdatingJob
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.stsformbasedauthwebconfigupdatingjob(v=AX.60)
ms:contentKeyID: 62206063
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.STSFormBasedAuthWebConfigUpdatingJob
dev_langs:
- CSharp
- C++
- VB
---

# STSFormBasedAuthWebConfigUpdatingJob Class

Job that installs web.config file changes in the STS. STS does not seem to be supported by the "normal" web.config-updating infrastructure, hence we do this directly via editing the xml.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public MustInherit Class STSFormBasedAuthWebConfigUpdatingJob _
    Inherits SPJobDefinition
'Usage
Dim instance As STSFormBasedAuthWebConfigUpdatingJob
```

``` csharp
public abstract class STSFormBasedAuthWebConfigUpdatingJob : SPJobDefinition
```

``` c++
public ref class STSFormBasedAuthWebConfigUpdatingJob abstract : public SPJobDefinition
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  SPAutoSerializingObject  
    SPPersistedObject  
      SPJobDefinition  
        Microsoft.Dynamics.Retail.SP.CommonFeatures.STSFormBasedAuthWebConfigUpdatingJob  
          [Microsoft.Dynamics.Retail.SP.CommonFeatures.STSFormBasedAuthWebConfigActivationJob](stsformbasedauthwebconfigactivationjob-class-microsoft-dynamics-retail-sp-commonfeatures.md)  
          [Microsoft.Dynamics.Retail.SP.CommonFeatures.STSFormBasedAuthWebConfigDeactivationJob](stsformbasedauthwebconfigdeactivationjob-class-microsoft-dynamics-retail-sp-commonfeatures.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

