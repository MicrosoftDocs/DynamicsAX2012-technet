---
title: EmployeeLogOnStoreDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: EmployeeLogOnStoreDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EmployeeLogOnStoreDataRequest.#ctor(System.Int64,System.String,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType,System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.employeelogonstoredatarequest.employeelogonstoredatarequest(v=AX.60)
ms:contentKeyID: 65317323
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EmployeeLogOnStoreDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeLogOnStoreDataRequest Constructor

Initializes a new instance of the [EmployeeLogOnStoreDataRequest](employeelogonstoredatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

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
    extraData As String, _
    columnSet As ColumnSet _
)
'Usage
Dim channelId As Long
Dim staffId As String
Dim passwordHash As String
Dim logOnKeyHash As String
Dim logOnType As LogOnType
Dim extraData As String
Dim columnSet As ColumnSet

Dim instance As New EmployeeLogOnStoreDataRequest(channelId, _
    staffId, passwordHash, logOnKeyHash, _
    logOnType, extraData, columnSet)
```

``` csharp
public EmployeeLogOnStoreDataRequest(
    long channelId,
    string staffId,
    string passwordHash,
    string logOnKeyHash,
    LogOnType logOnType,
    string extraData,
    ColumnSet columnSet
)
```

``` c++
public:
EmployeeLogOnStoreDataRequest(
    long long channelId, 
    String^ staffId, 
    String^ passwordHash, 
    String^ logOnKeyHash, 
    LogOnType logOnType, 
    String^ extraData, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - passwordHash  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logOnKeyHash  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logOnType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType](logontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - extraData  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[EmployeeLogOnStoreDataRequest Class](employeelogonstoredatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

