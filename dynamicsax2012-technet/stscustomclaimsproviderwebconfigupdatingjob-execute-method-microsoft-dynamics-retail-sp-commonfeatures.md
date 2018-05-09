---
title: STSCustomClaimsProviderWebConfigUpdatingJob.Execute Method  (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: Execute Method
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.STSCustomClaimsProviderWebConfigUpdatingJob.Execute(System.Guid)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.stscustomclaimsproviderwebconfigupdatingjob.execute(v=AX.60)
ms:contentKeyID: 62203872
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SP.CommonFeatures.STSCustomClaimsProviderWebConfigUpdatingJob.Execute
dev_langs:
- CSharp
- C++
- VB
---

# Execute Method

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
Dim instance As STSCustomClaimsProviderWebConfigUpdatingJob
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
    Type: [System.Guid](https://technet.microsoft.com/en-us/library/cey1zx63\(v=ax.60\))  

## See Also

#### Reference

[STSCustomClaimsProviderWebConfigUpdatingJob Class](stscustomclaimsproviderwebconfigupdatingjob-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

