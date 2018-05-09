---
title: GetCommerceListServiceRequest.PublicFilter Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PublicFilter Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCommerceListServiceRequest.PublicFilter
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getcommercelistservicerequest.publicfilter(v=AX.60)
ms:contentKeyID: 62209390
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCommerceListServiceRequest.PublicFilter
dev_langs:
- CSharp
- C++
- VB
---

# PublicFilter Property

Gets or sets a value indicating whether the commerce lists should be filtered by public.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PublicFilter As Boolean
    Get
    Set
'Usage
Dim instance As GetCommerceListServiceRequest
Dim value As Boolean

value = instance.PublicFilter

instance.PublicFilter = value
```

``` csharp
[DataMemberAttribute]
public bool PublicFilter { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool PublicFilter {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetCommerceListServiceRequest Class](getcommercelistservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

