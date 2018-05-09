---
title: MetadataFilterProvider.GetFilters Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions)
TOCTitle: GetFilters Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.MetadataFilterProvider.GetFilters(System.Web.Http.HttpConfiguration,System.Web.Http.Controllers.HttpActionDescriptor)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odataextensions.metadatafilterprovider.getfilters(v=AX.60)
ms:contentKeyID: 62202381
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.MetadataFilterProvider.GetFilters
dev_langs:
- CSharp
- C++
- VB
---

# GetFilters Method

Returns filters for metadata controller.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Function GetFilters ( _
    configuration As HttpConfiguration, _
    actionDescriptor As HttpActionDescriptor _
) As IEnumerable(Of FilterInfo)
'Usage
Dim instance As MetadataFilterProvider
Dim configuration As HttpConfiguration
Dim actionDescriptor As HttpActionDescriptor
Dim returnValue As IEnumerable(Of FilterInfo)

returnValue = instance.GetFilters(configuration, _
    actionDescriptor)
```

``` csharp
public IEnumerable<FilterInfo> GetFilters(
    HttpConfiguration configuration,
    HttpActionDescriptor actionDescriptor
)
```

``` c++
public:
virtual IEnumerable<FilterInfo^>^ GetFilters(
    HttpConfiguration^ configuration, 
    HttpActionDescriptor^ actionDescriptor
) sealed
```

#### Parameters

  - configuration  
    Type: HttpConfiguration  

<!-- end list -->

  - actionDescriptor  
    Type: HttpActionDescriptor  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<FilterInfo\>  
A collection of filters.  

#### Implements

IFilterProviderGetFilters(HttpConfiguration, HttpActionDescriptor)  

## See Also

#### Reference

[MetadataFilterProvider Class](metadatafilterprovider-class-microsoft-dynamics-retail-retailserverlibrary-odataextensions.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions Namespace](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)

