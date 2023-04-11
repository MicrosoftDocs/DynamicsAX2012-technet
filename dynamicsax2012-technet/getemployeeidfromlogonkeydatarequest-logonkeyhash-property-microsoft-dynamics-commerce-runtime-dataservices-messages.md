---
title: GetEmployeeIdFromLogOnKeyDataRequest.LogOnKeyHash Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: LogOnKeyHash Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeIdFromLogOnKeyDataRequest.LogOnKeyHash
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getemployeeidfromlogonkeydatarequest.logonkeyhash(v=AX.60)
ms:contentKeyID: 65320711
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetEmployeeIdFromLogOnKeyDataRequest.LogOnKeyHash
dev_langs:
- CSharp
- C++
- VB
---

# LogOnKeyHash Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the log on key hash.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogOnKeyHash As String
    Get
    Private Set
'Usage
Dim instance As GetEmployeeIdFromLogOnKeyDataRequest
Dim value As String

value = instance.LogOnKeyHash
```

``` csharp
[DataMemberAttribute]
public string LogOnKeyHash { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LogOnKeyHash {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The log on key hash.  

## See Also

#### Reference

[GetEmployeeIdFromLogOnKeyDataRequest Class](getemployeeidfromlogonkeydatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

