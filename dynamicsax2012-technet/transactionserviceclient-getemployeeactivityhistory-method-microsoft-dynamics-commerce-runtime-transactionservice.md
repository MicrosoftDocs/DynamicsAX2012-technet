---
title: TransactionServiceClient.GetEmployeeActivityHistory Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetEmployeeActivityHistory Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetEmployeeActivityHistory(System.String,System.String,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo,Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getemployeeactivityhistory(v=AX.60)
ms:contentKeyID: 65321363
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetEmployeeActivityHistory
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeeActivityHistory Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetEmployeeActivityHistory ( _
    staffId As String, _
    storeId As String, _
    fromUtcDateTime As Nullable(Of DateTimeOffset), _
    toUtcDateTime As Nullable(Of DateTimeOffset), _
    pagingInfo As PagingInfo, _
    sortingInfo As SortingInfo _
) As PagedResult(Of EmployeeActivity)
'Usage
Dim instance As TransactionServiceClient
Dim staffId As String
Dim storeId As String
Dim fromUtcDateTime As Nullable(Of DateTimeOffset)
Dim toUtcDateTime As Nullable(Of DateTimeOffset)
Dim pagingInfo As PagingInfo
Dim sortingInfo As SortingInfo
Dim returnValue As PagedResult(Of EmployeeActivity)

returnValue = instance.GetEmployeeActivityHistory(staffId, _
    storeId, fromUtcDateTime, toUtcDateTime, _
    pagingInfo, sortingInfo)
```

``` csharp
public PagedResult<EmployeeActivity> GetEmployeeActivityHistory(
    string staffId,
    string storeId,
    Nullable<DateTimeOffset> fromUtcDateTime,
    Nullable<DateTimeOffset> toUtcDateTime,
    PagingInfo pagingInfo,
    SortingInfo sortingInfo
)
```

``` c++
public:
PagedResult<EmployeeActivity^>^ GetEmployeeActivityHistory(
    String^ staffId, 
    String^ storeId, 
    Nullable<DateTimeOffset> fromUtcDateTime, 
    Nullable<DateTimeOffset> toUtcDateTime, 
    PagingInfo^ pagingInfo, 
    SortingInfo^ sortingInfo
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - fromUtcDateTime  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))\>  

<!-- end list -->

  - toUtcDateTime  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))\>  

<!-- end list -->

  - pagingInfo  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - sortingInfo  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[EmployeeActivity](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

