---
title: SaveCommerceListServiceResponse.CommerceList Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CommerceList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCommerceListServiceResponse.CommerceList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savecommercelistserviceresponse.commercelist(v=AX.60)
ms:contentKeyID: 62206198
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCommerceListServiceResponse.CommerceList
dev_langs:
- CSharp
- C++
- VB
---

# CommerceList Property

Gets the updated commerce list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CommerceList As CommerceList
    Get
    Private Set
'Usage
Dim instance As SaveCommerceListServiceResponse
Dim value As CommerceList

value = instance.CommerceList
```

``` csharp
[DataMemberAttribute]
public CommerceList CommerceList { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property CommerceList^ CommerceList {
    CommerceList^ get ();
    private: void set (CommerceList^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveCommerceListServiceResponse Class](savecommercelistserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

