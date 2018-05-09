---
title: GetEmployeeActivityHistoryServiceRequest.UserId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: UserId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmployeeActivityHistoryServiceRequest.UserId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getemployeeactivityhistoryservicerequest.userid(v=AX.60)
ms:contentKeyID: 65320101
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmployeeActivityHistoryServiceRequest.UserId
dev_langs:
- CSharp
- C++
- VB
---

# UserId Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UserId As String
    Get
    Private Set
'Usage
Dim instance As GetEmployeeActivityHistoryServiceRequest
Dim value As String

value = instance.UserId
```

``` csharp
[DataMemberAttribute]
public string UserId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ UserId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetEmployeeActivityHistoryServiceRequest Class](getemployeeactivityhistoryservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

