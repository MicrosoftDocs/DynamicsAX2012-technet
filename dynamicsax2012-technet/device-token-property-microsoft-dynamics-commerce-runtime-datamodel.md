---
title: Device.Token Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Token Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Device.Token
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.device.token(v=AX.60)
ms:contentKeyID: 62209685
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Device.Token
dev_langs:
- CSharp
- C++
- VB
---

# Token Property

Gets or sets the device token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Token As String
    Get
    Set
'Usage
Dim instance As Device
Dim value As String

value = instance.Token

instance.Token = value
```

``` csharp
[DataMemberAttribute]
public string Token { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Token {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The device token.  

## See Also

#### Reference

[Device Class](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

