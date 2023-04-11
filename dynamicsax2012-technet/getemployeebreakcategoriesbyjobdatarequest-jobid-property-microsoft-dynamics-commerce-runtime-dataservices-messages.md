---
title: GetEmployeeBreakCategoriesByJobDataRequest.JobId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: JobId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeBreakCategoriesByJobDataRequest.JobId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getemployeebreakcategoriesbyjobdatarequest.jobid(v=AX.60)
ms:contentKeyID: 65321745
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeBreakCategoriesByJobDataRequest.JobId
dev_langs:
- CSharp
- C++
- VB
---

# JobId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the job identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property JobId As String
    Get
    Private Set
'Usage
Dim instance As GetEmployeeBreakCategoriesByJobDataRequest
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
The job identifier.  

## See Also

#### Reference

[GetEmployeeBreakCategoriesByJobDataRequest Class](getemployeebreakcategoriesbyjobdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

