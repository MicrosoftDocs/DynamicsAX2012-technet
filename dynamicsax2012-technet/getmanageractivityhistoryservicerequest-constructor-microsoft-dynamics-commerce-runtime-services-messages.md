---
title: GetManagerActivityHistoryServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetManagerActivityHistoryServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetManagerActivityHistoryServiceRequest.#ctor(System.String[],Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType[],System.String[],System.Nullable{System.DateTime},System.Nullable{System.DateTime},Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo,Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getmanageractivityhistoryservicerequest.getmanageractivityhistoryservicerequest(v=AX.60)
ms:contentKeyID: 65316644
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetManagerActivityHistoryServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetManagerActivityHistoryServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    storeIds As String(), _
    employeeActivityTypes As EmployeeActivityType(), _
    breakActivities As String(), _
    fromUtcDateTime As Nullable(Of DateTime), _
    toUtcDateTime As Nullable(Of DateTime), _
    pagingInfo As PagingInfo, _
    sortingInfo As SortingInfo _
)
'Usage
Dim storeIds As String()
Dim employeeActivityTypes As EmployeeActivityType()
Dim breakActivities As String()
Dim fromUtcDateTime As Nullable(Of DateTime)
Dim toUtcDateTime As Nullable(Of DateTime)
Dim pagingInfo As PagingInfo
Dim sortingInfo As SortingInfo

Dim instance As New GetManagerActivityHistoryServiceRequest(storeIds, _
    employeeActivityTypes, breakActivities, _
    fromUtcDateTime, toUtcDateTime, _
    pagingInfo, sortingInfo)
```

``` csharp
public GetManagerActivityHistoryServiceRequest(
    string[] storeIds,
    EmployeeActivityType[] employeeActivityTypes,
    string[] breakActivities,
    Nullable<DateTime> fromUtcDateTime,
    Nullable<DateTime> toUtcDateTime,
    PagingInfo pagingInfo,
    SortingInfo sortingInfo
)
```

``` c++
public:
GetManagerActivityHistoryServiceRequest(
    array<String^>^ storeIds, 
    array<EmployeeActivityType>^ employeeActivityTypes, 
    array<String^>^ breakActivities, 
    Nullable<DateTime> fromUtcDateTime, 
    Nullable<DateTime> toUtcDateTime, 
    PagingInfo^ pagingInfo, 
    SortingInfo^ sortingInfo
)
```

#### Parameters

  - storeIds  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\[\]  

<!-- end list -->

  - employeeActivityTypes  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType](employeeactivitytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\[\]  

<!-- end list -->

  - breakActivities  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\[\]  

<!-- end list -->

  - fromUtcDateTime  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))\>  

<!-- end list -->

  - toUtcDateTime  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))\>  

<!-- end list -->

  - pagingInfo  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - sortingInfo  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetManagerActivityHistoryServiceRequest Class](getmanageractivityhistoryservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

