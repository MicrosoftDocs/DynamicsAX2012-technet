---
title: EmployeeLogOnStoreDataRequest.ExtraData Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ExtraData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EmployeeLogOnStoreDataRequest.ExtraData
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.employeelogonstoredatarequest.extradata(v=AX.60)
ms:contentKeyID: 65319862
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EmployeeLogOnStoreDataRequest.ExtraData
dev_langs:
- CSharp
- C++
- VB
---

# ExtraData Property

Gets extra data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ExtraData As String
    Get
    Private Set
'Usage
Dim instance As EmployeeLogOnStoreDataRequest
Dim value As String

value = instance.ExtraData
```

``` csharp
[DataMemberAttribute]
public string ExtraData { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ExtraData {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The extra data.  

## See Also

#### Reference

[EmployeeLogOnStoreDataRequest Class](employeelogonstoredatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

