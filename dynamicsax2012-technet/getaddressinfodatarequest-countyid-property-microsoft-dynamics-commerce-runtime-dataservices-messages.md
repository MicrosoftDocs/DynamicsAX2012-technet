---
title: GetAddressInfoDataRequest.CountyId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CountyId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressInfoDataRequest.CountyId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getaddressinfodatarequest.countyid(v=AX.60)
ms:contentKeyID: 65322345
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressInfoDataRequest.CountyId
dev_langs:
- CSharp
- C++
- VB
---

# CountyId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the county identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CountyId As String
    Get
    Protected Set
'Usage
Dim instance As GetAddressInfoDataRequest
Dim value As String

value = instance.CountyId

instance.CountyId = value
```

``` csharp
[DataMemberAttribute]
public string CountyId { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CountyId {
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

