---
title: GetTillLayoutDataServiceRequest.UserId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: UserId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTillLayoutDataServiceRequest.UserId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.gettilllayoutdataservicerequest.userid(v=AX.60)
ms:contentKeyID: 65322116
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTillLayoutDataServiceRequest.UserId
dev_langs:
- CSharp
- C++
- VB
---

# UserId Property

Gets the user identifier if specified.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UserId As String
    Get
    Private Set
'Usage
Dim instance As GetTillLayoutDataServiceRequest
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

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetTillLayoutDataServiceRequest Class](gettilllayoutdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

