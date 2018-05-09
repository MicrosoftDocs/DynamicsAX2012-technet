---
title: GetAddressRequest.CountryRegionId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CountryRegionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest.CountryRegionId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getaddressrequest.countryregionid(v=AX.60)
ms:contentKeyID: 62202074
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest.CountryRegionId
dev_langs:
- CSharp
- C++
- VB
---

# CountryRegionId Property

Gets or sets the country region identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CountryRegionId As String
    Get
    Set
'Usage
Dim instance As GetAddressRequest
Dim value As String

value = instance.CountryRegionId

instance.CountryRegionId = value
```

``` csharp
[DataMemberAttribute]
public string CountryRegionId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CountryRegionId {
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

