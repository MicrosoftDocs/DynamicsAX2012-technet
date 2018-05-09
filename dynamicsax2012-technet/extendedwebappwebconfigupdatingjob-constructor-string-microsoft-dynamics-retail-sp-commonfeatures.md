---
title: ExtendedWebAppWebConfigUpdatingJob Constructor (String, ) (Microsoft.Dynamics.Retail.SP.CommonFeatures)
TOCTitle: ExtendedWebAppWebConfigUpdatingJob Constructor (String, )
ms:assetid: M:Microsoft.Dynamics.Retail.SP.CommonFeatures.ExtendedWebAppWebConfigUpdatingJob.#ctor(System.String,Microsoft.SharePoint.Administration.SPWebApplication)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sp.commonfeatures.extendedwebappwebconfigupdatingjob.extendedwebappwebconfigupdatingjob(v=AX.60)
ms:contentKeyID: 62201912
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ExtendedWebAppWebConfigUpdatingJob Constructor (String, )

Initializes a new instance of the ExtendedWebAppWebConfigUpdatingJob class and provides parameters for specifying key objects.

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

Dim instance As New ExtendedWebAppWebConfigUpdatingJob(jobName, _
    webApplication)
```

``` csharp
public ExtendedWebAppWebConfigUpdatingJob(
    string jobName,
    SPWebApplication webApplication
)
```

``` c++
public:
ExtendedWebAppWebConfigUpdatingJob(
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

[ExtendedWebAppWebConfigUpdatingJob Class](extendedwebappwebconfigupdatingjob-class-microsoft-dynamics-retail-sp-commonfeatures.md)

[ExtendedWebAppWebConfigUpdatingJob Overload](extendedwebappwebconfigupdatingjob-constructor-microsoft-dynamics-retail-sp-commonfeatures.md)

[Microsoft.Dynamics.Retail.SP.CommonFeatures Namespace](microsoft-dynamics-retail-sp-commonfeatures-namespace.md)

