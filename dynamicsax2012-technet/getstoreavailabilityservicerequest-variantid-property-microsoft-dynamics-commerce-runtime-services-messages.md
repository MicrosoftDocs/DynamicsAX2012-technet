---
title: GetStoreAvailabilityServiceRequest.VariantId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: VariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoreAvailabilityServiceRequest.VariantId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getstoreavailabilityservicerequest.variantid(v=AX.60)
ms:contentKeyID: 65320523
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoreAvailabilityServiceRequest.VariantId
dev_langs:
- CSharp
- C++
- VB
---

# VariantId Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property VariantId As String
    Get
    Private Set
'Usage
Dim instance As GetStoreAvailabilityServiceRequest
Dim value As String

value = instance.VariantId
```

``` csharp
[DataMemberAttribute]
public string VariantId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ VariantId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetStoreAvailabilityServiceRequest Class](getstoreavailabilityservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

