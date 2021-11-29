---
title: GetEmployeeIdFromLogOnKeyDataRequest.LogOnType Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: LogOnType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeIdFromLogOnKeyDataRequest.LogOnType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getemployeeidfromlogonkeydatarequest.logontype(v=AX.60)
ms:contentKeyID: 65318394
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeIdFromLogOnKeyDataRequest.LogOnType
dev_langs:
- CSharp
- C++
- VB
---

# LogOnType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the type of the log on.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogOnType As LogOnType
    Get
    Private Set
'Usage
Dim instance As GetEmployeeIdFromLogOnKeyDataRequest
Dim value As LogOnType

value = instance.LogOnType
```

``` csharp
[DataMemberAttribute]
public LogOnType LogOnType { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property LogOnType LogOnType {
    LogOnType get ();
    private: void set (LogOnType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType](logontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The type of the log on.  

## See Also

#### Reference

[GetEmployeeIdFromLogOnKeyDataRequest Class](getemployeeidfromlogonkeydatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

