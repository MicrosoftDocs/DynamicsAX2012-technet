---
title: GetItemByIdRequest.ProductIds Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ProductIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemByIdRequest.ProductIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getitembyidrequest.productids(v=AX.60)
ms:contentKeyID: 62206083
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemByIdRequest.ProductIds
dev_langs:
- CSharp
- C++
- VB
---

# ProductIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of product identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductIds As Collection(Of Long)
    Get
    Private Set
'Usage
Dim instance As GetItemByIdRequest
Dim value As Collection(Of Long)

value = instance.ProductIds
```

``` csharp
[DataMemberAttribute]
public Collection<long> ProductIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<long long>^ ProductIds {
    Collection<long long>^ get ();
    private: void set (Collection<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[GetItemByIdRequest Class](getitembyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

