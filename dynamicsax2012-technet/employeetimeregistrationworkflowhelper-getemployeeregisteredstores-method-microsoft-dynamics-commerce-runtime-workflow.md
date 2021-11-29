---
title: EmployeeTimeRegistrationWorkflowHelper.GetEmployeeRegisteredStores Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetEmployeeRegisteredStores Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.GetEmployeeRegisteredStores(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.employeetimeregistrationworkflowhelper.getemployeeregisteredstores(v=AX.60)
ms:contentKeyID: 65321408
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.GetEmployeeRegisteredStores
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeeRegisteredStores Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetEmployeeRegisteredStores ( _
    context As RequestContext, _
    resultSettings As QueryResultSettings _
) As ReadOnlyCollection(Of OrgUnit)
'Usage
Dim context As RequestContext
Dim resultSettings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of OrgUnit)

returnValue = EmployeeTimeRegistrationWorkflowHelper.GetEmployeeRegisteredStores(context, _
    resultSettings)
```

``` csharp
public static ReadOnlyCollection<OrgUnit> GetEmployeeRegisteredStores(
    RequestContext context,
    QueryResultSettings resultSettings
)
```

``` c++
public:
static ReadOnlyCollection<OrgUnit^>^ GetEmployeeRegisteredStores(
    RequestContext^ context, 
    QueryResultSettings^ resultSettings
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - resultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[EmployeeTimeRegistrationWorkflowHelper Class](employeetimeregistrationworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

