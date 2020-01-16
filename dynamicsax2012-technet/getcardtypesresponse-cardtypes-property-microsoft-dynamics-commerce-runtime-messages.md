---
title: GetCardTypesResponse.CardTypes Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CardTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCardTypesResponse.CardTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcardtypesresponse.cardtypes(v=AX.60)
ms:contentKeyID: 62208016
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCardTypesResponse.CardTypes
dev_langs:
- CSharp
- C++
- VB
---

# CardTypes Property

Gets the CardType collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardTypes As ReadOnlyCollection(Of CardTypeInfo)
    Get
    Private Set
'Usage
Dim instance As GetCardTypesResponse
Dim value As ReadOnlyCollection(Of CardTypeInfo)

value = instance.CardTypes
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<CardTypeInfo> CardTypes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<CardTypeInfo^>^ CardTypes {
    ReadOnlyCollection<CardTypeInfo^>^ get ();
    private: void set (ReadOnlyCollection<CardTypeInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CardTypeInfo](cardtypeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetCardTypesResponse Class](getcardtypesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

