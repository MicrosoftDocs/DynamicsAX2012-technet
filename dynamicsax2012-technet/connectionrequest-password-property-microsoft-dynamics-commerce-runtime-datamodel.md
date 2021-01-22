---
title: ConnectionRequest.Password Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Password Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest.Password
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.connectionrequest.password(v=AX.60)
ms:contentKeyID: 62211004
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest.Password
dev_langs:
- CSharp
- C++
- VB
---

# Password Property

Gets or sets the staff password.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Password As String
    Get
    Set
'Usage
Dim instance As ConnectionRequest
Dim value As String

value = instance.Password

instance.Password = value
```

``` csharp
[DataMemberAttribute]
public string Password { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Password {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The staff password.  

## See Also

#### Reference

[ConnectionRequest Class](connectionrequest-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

