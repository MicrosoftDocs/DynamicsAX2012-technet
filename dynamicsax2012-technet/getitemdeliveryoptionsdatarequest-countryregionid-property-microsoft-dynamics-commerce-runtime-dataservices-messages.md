---
title: GetItemDeliveryOptionsDataRequest.CountryRegionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CountryRegionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemDeliveryOptionsDataRequest.CountryRegionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getitemdeliveryoptionsdatarequest.countryregionid(v=AX.60)
ms:contentKeyID: 65319654
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemDeliveryOptionsDataRequest.CountryRegionId
dev_langs:
- CSharp
- C++
- VB
---

# CountryRegionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the country region id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CountryRegionId As String
    Get
    Private Set
'Usage
Dim instance As GetItemDeliveryOptionsDataRequest
Dim value As String

value = instance.CountryRegionId
```

``` csharp
[DataMemberAttribute]
public string CountryRegionId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CountryRegionId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetItemDeliveryOptionsDataRequest Class](getitemdeliveryoptionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

