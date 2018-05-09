---
title: ValidateEmployeePasswordDataRequest.LogOnType Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: LogOnType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateEmployeePasswordDataRequest.LogOnType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.validateemployeepassworddatarequest.logontype(v=AX.60)
ms:contentKeyID: 65316404
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateEmployeePasswordDataRequest.LogOnType
dev_langs:
- CSharp
- C++
- VB
---

# LogOnType Property

Gets the logon type.

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
Dim instance As ValidateEmployeePasswordDataRequest
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
The logon type.  

## See Also

#### Reference

[ValidateEmployeePasswordDataRequest Class](validateemployeepassworddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

