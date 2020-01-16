---
title: STSCustomClaimsProviderWebConfigActivationJob Constructor (String, ) (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: STSCustomClaimsProviderWebConfigActivationJob Constructor (String, )
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.STSCustomClaimsProviderWebConfigActivationJob.#ctor(System.String,Microsoft.SharePoint.Administration.SPWebApplication)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sp.commonfeatures.stscustomclaimsproviderwebconfigactivationjob.stscustomclaimsproviderwebconfigactivationjob(v=AX.60)
ms:contentKeyID: 62207598
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# STSCustomClaimsProviderWebConfigActivationJob Constructor (String, )

Initializes a new instance of the STSCustomClaimsProviderWebConfigActivationJob class and provides parameters for specifying key objects.

**Namespace:**  [Microsoft.Dynamics.Retail.SP.CommonFeatures](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Storefront (in Microsoft.Dynamics.Retail.SP.Web.Storefront.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    jobName As String, _
    webApplication As SPWebApplication _
)
'Usage
Dim jobName As String
Dim webApplication As SPWebApplication

Dim instance As New STSCustomClaimsProviderWebConfigActivationJob(jobName, _
    webApplication)
```

``` csharp
public STSCustomClaimsProviderWebConfigActivationJob(
    string jobName,
    SPWebApplication webApplication
)
```

``` c++
public:
STSCustomClaimsProviderWebConfigActivationJob(
    String^ jobName, 
    SPWebApplication^ webApplication
)
```

#### Parameters

  - jobName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - webApplication  
    Type: SPWebApplication  

## See Also

#### Reference

[STSCustomClaimsProviderWebConfigActivationJob Class](stscustomclaimsproviderwebconfigactivationjob-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[STSCustomClaimsProviderWebConfigActivationJob Overload](stscustomclaimsproviderwebconfigactivationjob-constructor-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

