---
title: GetEmployeeActivityHistoryServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetEmployeeActivityHistoryServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmployeeActivityHistoryServiceRequest.#ctor(System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo,Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getemployeeactivityhistoryservicerequest.getemployeeactivityhistoryservicerequest(v=AX.60)
ms:contentKeyID: 65318293
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmployeeActivityHistoryServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeeActivityHistoryServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    userId As String, _
    storeNumber As String, _
    fromUtcDateTime As Nullable(Of DateTime), _
    toUtcDateTime As Nullable(Of DateTime), _
    pagingInfo As PagingInfo, _
    sortingInfo As SortingInfo _
)
'Usage
Dim userId As String
Dim storeNumber As String
Dim fromUtcDateTime As Nullable(Of DateTime)
Dim toUtcDateTime As Nullable(Of DateTime)
Dim pagingInfo As PagingInfo
Dim sortingInfo As SortingInfo

Dim instance As New GetEmployeeActivityHistoryServiceRequest(userId, _
    storeNumber, fromUtcDateTime, toUtcDateTime, _
    pagingInfo, sortingInfo)
```

``` csharp
public GetEmployeeActivityHistoryServiceRequest(
    string userId,
    string storeNumber,
    Nullable<DateTime> fromUtcDateTime,
    Nullable<DateTime> toUtcDateTime,
    PagingInfo pagingInfo,
    SortingInfo sortingInfo
)
```

``` c++
public:
GetEmployeeActivityHistoryServiceRequest(
    String^ userId, 
    String^ storeNumber, 
    Nullable<DateTime> fromUtcDateTime, 
    Nullable<DateTime> toUtcDateTime, 
    PagingInfo^ pagingInfo, 
    SortingInfo^ sortingInfo
)
```

#### Parameters

  - userId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - fromUtcDateTime  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))\>  

<!-- end list -->

  - toUtcDateTime  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))\>  

<!-- end list -->

  - pagingInfo  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - sortingInfo  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetEmployeeActivityHistoryServiceRequest Class](getemployeeactivityhistoryservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

