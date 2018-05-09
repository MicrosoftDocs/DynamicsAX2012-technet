---
title: ConnectionRequest.UserId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UserId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest.UserId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.connectionrequest.userid(v=AX.60)
ms:contentKeyID: 62208417
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest.UserId
dev_langs:
- CSharp
- C++
- VB
---

# UserId Property

Gets or sets the staff identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UserId As String
    Get
    Set
'Usage
Dim instance As ConnectionRequest
Dim value As String

value = instance.UserId

instance.UserId = value
```

``` csharp
[DataMemberAttribute]
public string UserId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ UserId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The staff identifier.  

## See Also

#### Reference

[ConnectionRequest Class](connectionrequest-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

