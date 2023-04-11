---
title: EmployeeTimeRegistrationWorkflowHelper.GetEmployeeLogbookDetails Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetEmployeeLogbookDetails Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.GetEmployeeLogbookDetails(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo,Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.employeetimeregistrationworkflowhelper.getemployeelogbookdetails(v=AX.60)
ms:contentKeyID: 65316161
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.GetEmployeeLogbookDetails
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeeLogbookDetails Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetEmployeeLogbookDetails ( _
    context As RequestContext, _
    storeNumber As String, _
    fromDateTimeOffset As Nullable(Of DateTimeOffset), _
    toDateTimeOffset As Nullable(Of DateTimeOffset), _
    pagingInfo As PagingInfo, _
    sortingInfo As SortingInfo _
) As ReadOnlyCollection(Of EmployeeActivity)
'Usage
Dim context As RequestContext
Dim storeNumber As String
Dim fromDateTimeOffset As Nullable(Of DateTimeOffset)
Dim toDateTimeOffset As Nullable(Of DateTimeOffset)
Dim pagingInfo As PagingInfo
Dim sortingInfo As SortingInfo
Dim returnValue As ReadOnlyCollection(Of EmployeeActivity)

returnValue = EmployeeTimeRegistrationWorkflowHelper.GetEmployeeLogbookDetails(context, _
    storeNumber, fromDateTimeOffset, _
    toDateTimeOffset, pagingInfo, sortingInfo)
```

``` csharp
public static ReadOnlyCollection<EmployeeActivity> GetEmployeeLogbookDetails(
    RequestContext context,
    string storeNumber,
    Nullable<DateTimeOffset> fromDateTimeOffset,
    Nullable<DateTimeOffset> toDateTimeOffset,
    PagingInfo pagingInfo,
    SortingInfo sortingInfo
)
```

``` c++
public:
static ReadOnlyCollection<EmployeeActivity^>^ GetEmployeeLogbookDetails(
    RequestContext^ context, 
    String^ storeNumber, 
    Nullable<DateTimeOffset> fromDateTimeOffset, 
    Nullable<DateTimeOffset> toDateTimeOffset, 
    PagingInfo^ pagingInfo, 
    SortingInfo^ sortingInfo
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - storeNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - fromDateTimeOffset  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  

<!-- end list -->

  - toDateTimeOffset  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  

<!-- end list -->

  - pagingInfo  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - sortingInfo  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[EmployeeActivity](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[EmployeeTimeRegistrationWorkflowHelper Class](employeetimeregistrationworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

