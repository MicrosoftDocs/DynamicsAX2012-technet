---
title: RegisterEmployeeBreakServiceRequest.JobId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: JobId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RegisterEmployeeBreakServiceRequest.JobId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.registeremployeebreakservicerequest.jobid(v=AX.60)
ms:contentKeyID: 65316646
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RegisterEmployeeBreakServiceRequest.JobId
dev_langs:
- CSharp
- C++
- VB
---

# JobId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property JobId As String
    Get
    Private Set
'Usage
Dim instance As RegisterEmployeeBreakServiceRequest
Dim value As String

value = instance.JobId
```

``` csharp
[DataMemberAttribute]
public string JobId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ JobId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[RegisterEmployeeBreakServiceRequest Class](registeremployeebreakservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

