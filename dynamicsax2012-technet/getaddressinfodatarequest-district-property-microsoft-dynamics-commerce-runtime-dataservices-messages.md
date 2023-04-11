---
title: GetAddressInfoDataRequest.District Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: District Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressInfoDataRequest.District
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getaddressinfodatarequest.district(v=AX.60)
ms:contentKeyID: 65321215
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressInfoDataRequest.District
dev_langs:
- CSharp
- C++
- VB
---

# District Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the district.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property District As String
    Get
    Protected Set
'Usage
Dim instance As GetAddressInfoDataRequest
Dim value As String

value = instance.District

instance.District = value
```

``` csharp
[DataMemberAttribute]
public string District { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ District {
    String^ get ();
    protected: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetAddressInfoDataRequest Class](getaddressinfodatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

