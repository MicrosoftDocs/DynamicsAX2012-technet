---
title: GetCommerceListResponse.CommerceLists Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CommerceLists Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCommerceListResponse.CommerceLists
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcommercelistresponse.commercelists(v=AX.60)
ms:contentKeyID: 62205126
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCommerceListResponse.CommerceLists
dev_langs:
- CSharp
- C++
- VB
---

# CommerceLists Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the commerce lists.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CommerceLists As ReadOnlyCollection(Of CommerceList)
    Get
    Private Set
'Usage
Dim instance As GetCommerceListResponse
Dim value As ReadOnlyCollection(Of CommerceList)

value = instance.CommerceLists
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<CommerceList> CommerceLists { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<CommerceList^>^ CommerceLists {
    ReadOnlyCollection<CommerceList^>^ get ();
    private: void set (ReadOnlyCollection<CommerceList^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetCommerceListResponse Class](getcommercelistresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

