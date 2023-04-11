---
title: STSFormBasedAuthWebConfigUpdatingJob.Execute Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: Execute Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.STSFormBasedAuthWebConfigUpdatingJob.Execute(System.Guid)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.stsformbasedauthwebconfigupdatingjob.execute(v=AX.60)
ms:contentKeyID: 62206682
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.STSFormBasedAuthWebConfigUpdatingJob.Execute
dev_langs:
- CSharp
- C++
- VB
---

# Execute Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the job definition on the local machine and is intended to be used only by the timer service.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Overrides Sub Execute ( _
    targetInstanceId As Guid _
)
'Usage
Dim instance As STSFormBasedAuthWebConfigUpdatingJob
Dim targetInstanceId As Guid

instance.Execute(targetInstanceId)
```

``` csharp
public override void Execute(
    Guid targetInstanceId
)
```

``` c++
public:
virtual void Execute(
    Guid targetInstanceId
) override
```

#### Parameters

  - targetInstanceId  
    Type: [System.Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))  

## See Also

#### Reference

[STSFormBasedAuthWebConfigUpdatingJob Class](stsformbasedauthwebconfigupdatingjob-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

