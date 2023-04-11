---
title: ValidateEmployeePasswordDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ValidateEmployeePasswordDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateEmployeePasswordDataRequest.#ctor(System.Int64,System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.validateemployeepassworddatarequest.validateemployeepassworddatarequest(v=AX.60)
ms:contentKeyID: 65322230
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateEmployeePasswordDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ValidateEmployeePasswordDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ValidateEmployeePasswordDataRequest](validateemployeepassworddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    staffId As String, _
    passwordHash As String, _
    logOnKeyHash As String, _
    logOnType As LogOnType, _
    columnSet As ColumnSet _
)
'Usage
Dim channelId As Long
Dim staffId As String
Dim passwordHash As String
Dim logOnKeyHash As String
Dim logOnType As LogOnType
Dim columnSet As ColumnSet

Dim instance As New ValidateEmployeePasswordDataRequest(channelId, _
    staffId, passwordHash, logOnKeyHash, _
    logOnType, columnSet)
```

``` csharp
public ValidateEmployeePasswordDataRequest(
    long channelId,
    string staffId,
    string passwordHash,
    string logOnKeyHash,
    LogOnType logOnType,
    ColumnSet columnSet
)
```

``` c++
public:
ValidateEmployeePasswordDataRequest(
    long long channelId, 
    String^ staffId, 
    String^ passwordHash, 
    String^ logOnKeyHash, 
    LogOnType logOnType, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - passwordHash  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logOnKeyHash  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logOnType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType](logontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[ValidateEmployeePasswordDataRequest Class](validateemployeepassworddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

