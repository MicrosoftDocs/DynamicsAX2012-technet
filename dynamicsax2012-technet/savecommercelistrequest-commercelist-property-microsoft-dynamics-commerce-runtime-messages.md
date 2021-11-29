---
title: SaveCommerceListRequest.CommerceList Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CommerceList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCommerceListRequest.CommerceList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savecommercelistrequest.commercelist(v=AX.60)
ms:contentKeyID: 62208595
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCommerceListRequest.CommerceList
dev_langs:
- CSharp
- C++
- VB
---

# CommerceList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the commerce list to udpate.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CommerceList As CommerceList
    Get
    Set
'Usage
Dim instance As SaveCommerceListRequest
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

[SaveCommerceListRequest Class](savecommercelistrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

