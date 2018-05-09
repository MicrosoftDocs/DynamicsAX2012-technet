---
title: STSCustomClaimsProviderWebConfigDeactivationJob Constructor (String, ) (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: STSCustomClaimsProviderWebConfigDeactivationJob Constructor (String, )
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.STSCustomClaimsProviderWebConfigDeactivationJob.#ctor(System.String,Microsoft.SharePoint.Administration.SPWebApplication)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.stscustomclaimsproviderwebconfigdeactivationjob.stscustomclaimsproviderwebconfigdeactivationjob(v=AX.60)
ms:contentKeyID: 62202740
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# STSCustomClaimsProviderWebConfigDeactivationJob Constructor (String, )

Initializes a new instance of the STSCustomClaimsProviderWebConfigDeactivationJob class and provides parameters for specifying key objects.

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

Dim instance As New STSCustomClaimsProviderWebConfigDeactivationJob(jobName, _
    webApplication)
```

``` csharp
public STSCustomClaimsProviderWebConfigDeactivationJob(
    string jobName,
    SPWebApplication webApplication
)
```

``` c++
public:
STSCustomClaimsProviderWebConfigDeactivationJob(
    String^ jobName, 
    SPWebApplication^ webApplication
)
```

#### Parameters

  - jobName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - webApplication  
    Type: SPWebApplication  

## See Also

#### Reference

[STSCustomClaimsProviderWebConfigDeactivationJob Class](stscustomclaimsproviderwebconfigdeactivationjob-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[STSCustomClaimsProviderWebConfigDeactivationJob Overload](stscustomclaimsproviderwebconfigdeactivationjob-constructor-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

