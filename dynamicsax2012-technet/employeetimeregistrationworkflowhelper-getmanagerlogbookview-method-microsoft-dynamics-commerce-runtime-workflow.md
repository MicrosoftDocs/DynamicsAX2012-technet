---
title: EmployeeTimeRegistrationWorkflowHelper.GetManagerLogbookView Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetManagerLogbookView Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.GetManagerLogbookView(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType[],System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo,Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.employeetimeregistrationworkflowhelper.getmanagerlogbookview(v=AX.60)
ms:contentKeyID: 65317561
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.EmployeeTimeRegistrationWorkflowHelper.GetManagerLogbookView
dev_langs:
- CSharp
- C++
- VB
---

# GetManagerLogbookView Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetManagerLogbookView ( _
    context As RequestContext, _
    storeNumber As String, _
    employeeActivityTypes As EmployeeActivityType(), _
    fromDateTimeOffset As Nullable(Of DateTimeOffset), _
    toDateTimeOffset As Nullable(Of DateTimeOffset), _
    pagingInfo As PagingInfo, _
    sortingInfo As SortingInfo _
) As ReadOnlyCollection(Of EmployeeActivity)
'Usage
Dim context As RequestContext
Dim storeNumber As String
Dim employeeActivityTypes As EmployeeActivityType()
Dim fromDateTimeOffset As Nullable(Of DateTimeOffset)
Dim toDateTimeOffset As Nullable(Of DateTimeOffset)
Dim pagingInfo As PagingInfo
Dim sortingInfo As SortingInfo
Dim returnValue As ReadOnlyCollection(Of EmployeeActivity)

returnValue = EmployeeTimeRegistrationWorkflowHelper.GetManagerLogbookView(context, _
    storeNumber, employeeActivityTypes, _
    fromDateTimeOffset, toDateTimeOffset, _
    pagingInfo, sortingInfo)
```

``` csharp
public static ReadOnlyCollection<EmployeeActivity> GetManagerLogbookView(
    RequestContext context,
    string storeNumber,
    EmployeeActivityType[] employeeActivityTypes,
    Nullable<DateTimeOffset> fromDateTimeOffset,
    Nullable<DateTimeOffset> toDateTimeOffset,
    PagingInfo pagingInfo,
    SortingInfo sortingInfo
)
```

``` c++
public:
static ReadOnlyCollection<EmployeeActivity^>^ GetManagerLogbookView(
    RequestContext^ context, 
    String^ storeNumber, 
    array<EmployeeActivityType>^ employeeActivityTypes, 
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
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - employeeActivityTypes  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType](employeeactivitytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\[\]  

<!-- end list -->

  - fromDateTimeOffset  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))\>  

<!-- end list -->

  - toDateTimeOffset  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))\>  

<!-- end list -->

  - pagingInfo  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - sortingInfo  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[EmployeeActivity](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[EmployeeTimeRegistrationWorkflowHelper Class](employeetimeregistrationworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

