---
title: GetEmployeeIdFromLogOnKeyDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetEmployeeIdFromLogOnKeyDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeIdFromLogOnKeyDataRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getemployeeidfromlogonkeydatarequest.getemployeeidfromlogonkeydatarequest(v=AX.60)
ms:contentKeyID: 65323042
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeIdFromLogOnKeyDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeeIdFromLogOnKeyDataRequest Constructor

Initializes a new instance of the [GetEmployeeIdFromLogOnKeyDataRequest](getemployeeidfromlogonkeydatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    logOnKeyHash As String, _
    logOnType As LogOnType _
)
'Usage
Dim logOnKeyHash As String
Dim logOnType As LogOnType

Dim instance As New GetEmployeeIdFromLogOnKeyDataRequest(logOnKeyHash, _
    logOnType)
```

``` csharp
public GetEmployeeIdFromLogOnKeyDataRequest(
    string logOnKeyHash,
    LogOnType logOnType
)
```

``` c++
public:
GetEmployeeIdFromLogOnKeyDataRequest(
    String^ logOnKeyHash, 
    LogOnType logOnType
)
```

#### Parameters

  - logOnKeyHash  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logOnType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType](logontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetEmployeeIdFromLogOnKeyDataRequest Class](getemployeeidfromlogonkeydatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

