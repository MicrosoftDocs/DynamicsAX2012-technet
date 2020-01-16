---
title: NonBindableActionController.SearchReportDataSet Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: SearchReportDataSet Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.SearchReportDataSet(System.Web.Http.OData.ODataActionParameters,System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportDataSet})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.searchreportdataset(v=AX.60)
ms:contentKeyID: 62201835
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.SearchReportDataSet
dev_langs:
- CSharp
- C++
- VB
---

# SearchReportDataSet Method

Searches all the report dataset filtered by Report Identifier, Parameters and Locale.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.ViewReport)> _
<HttpPostAttribute> _
Public Overridable Function SearchReportDataSet ( _
    parameters As ODataActionParameters, _
    queryOptions As ODataQueryOptions(Of ReportDataSet) _
) As ReportDataSet
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters
Dim queryOptions As ODataQueryOptions(Of ReportDataSet)
Dim returnValue As ReportDataSet

returnValue = instance.SearchReportDataSet(parameters, _
    queryOptions)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.ViewReport)]
[HttpPostAttribute]
public virtual ReportDataSet SearchReportDataSet(
    ODataActionParameters parameters,
    ODataQueryOptions<ReportDataSet> queryOptions
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::ViewReport)]
[HttpPostAttribute]
public:
virtual ReportDataSet^ SearchReportDataSet(
    ODataActionParameters^ parameters, 
    ODataQueryOptions<ReportDataSet^>^ queryOptions
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

<!-- end list -->

  - queryOptions  
    Type: ODataQueryOptions\<[ReportDataSet](reportdataset-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReportDataSet](reportdataset-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
A collection of cities.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

