---
title: SaveCommerceListServiceRequest.CommerceList Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CommerceList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCommerceListServiceRequest.CommerceList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savecommercelistservicerequest.commercelist(v=AX.60)
ms:contentKeyID: 62209812
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCommerceListServiceRequest.CommerceList
dev_langs:
- CSharp
- C++
- VB
---

# CommerceList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the commerce list to udpate.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CommerceList As CommerceList
    Get
    Set
'Usage
Dim instance As SaveCommerceListServiceRequest
Dim value As CommerceList

value = instance.CommerceList

instance.CommerceList = value
```

``` csharp
[DataMemberAttribute]
public CommerceList CommerceList { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property CommerceList^ CommerceList {
    CommerceList^ get ();
    void set (CommerceList^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveCommerceListServiceRequest Class](savecommercelistservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

