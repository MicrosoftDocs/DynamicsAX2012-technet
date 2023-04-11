---
title: GetItemByIdRequest.ItemIds Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ItemIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemByIdRequest.ItemIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getitembyidrequest.itemids(v=AX.60)
ms:contentKeyID: 49851009
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemByIdRequest.ItemIds
dev_langs:
- CSharp
- C++
- VB
---

# ItemIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of item identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemIds As Collection(Of String)
    Get
    Private Set
'Usage
Dim instance As GetItemByIdRequest
Dim value As Collection(Of String)

value = instance.ItemIds
```

``` csharp
[DataMemberAttribute]
public Collection<string> ItemIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<String^>^ ItemIds {
    Collection<String^>^ get ();
    private: void set (Collection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[GetItemByIdRequest Class](getitembyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

