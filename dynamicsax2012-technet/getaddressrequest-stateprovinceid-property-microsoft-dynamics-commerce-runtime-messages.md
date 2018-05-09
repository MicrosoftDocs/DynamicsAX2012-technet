---
title: GetAddressRequest.StateProvinceId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: StateProvinceId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest.StateProvinceId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getaddressrequest.stateprovinceid(v=AX.60)
ms:contentKeyID: 62207888
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest.StateProvinceId
dev_langs:
- CSharp
- C++
- VB
---

# StateProvinceId Property

Gets or sets the state province identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StateProvinceId As String
    Get
    Set
'Usage
Dim instance As GetAddressRequest
Dim value As String

value = instance.StateProvinceId

instance.StateProvinceId = value
```

``` csharp
[DataMemberAttribute]
public string StateProvinceId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ StateProvinceId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetAddressRequest Class](getaddressrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

