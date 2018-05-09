---
title: ConnectionRequest.DeviceToken Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceToken Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest.DeviceToken
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.connectionrequest.devicetoken(v=AX.60)
ms:contentKeyID: 62212424
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ConnectionRequest.DeviceToken
dev_langs:
- CSharp
- C++
- VB
---

# DeviceToken Property

Gets or sets the device token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeviceToken As String
    Get
    Set
'Usage
Dim instance As ConnectionRequest
Dim value As String

value = instance.DeviceToken

instance.DeviceToken = value
```

``` csharp
[DataMemberAttribute]
public string DeviceToken { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeviceToken {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The device token.  

## See Also

#### Reference

[ConnectionRequest Class](connectionrequest-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

