---
title: GetEmployeeActivityHistoryServiceRequest.SortingInfo Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SortingInfo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmployeeActivityHistoryServiceRequest.SortingInfo
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getemployeeactivityhistoryservicerequest.sortinginfo(v=AX.60)
ms:contentKeyID: 65319513
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmployeeActivityHistoryServiceRequest.SortingInfo
dev_langs:
- CSharp
- C++
- VB
---

# SortingInfo Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SortingInfo As SortingInfo
    Get
    Private Set
'Usage
Dim instance As GetEmployeeActivityHistoryServiceRequest
Dim value As SortingInfo

value = instance.SortingInfo
```

``` csharp
[DataMemberAttribute]
public SortingInfo SortingInfo { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property SortingInfo^ SortingInfo {
    SortingInfo^ get ();
    private: void set (SortingInfo^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SortingInfo](sortinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetEmployeeActivityHistoryServiceRequest Class](getemployeeactivityhistoryservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

