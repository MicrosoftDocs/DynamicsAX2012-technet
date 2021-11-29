---
title: GetChannelCategoryHierarchyResponse.ChannelCategories Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ChannelCategories Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryHierarchyResponse.ChannelCategories
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelcategoryhierarchyresponse.channelcategories(v=AX.60)
ms:contentKeyID: 49823082
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryHierarchyResponse.ChannelCategories
dev_langs:
- CSharp
- C++
- VB
---

# ChannelCategories Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel categories.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelCategories As ReadOnlyCollection(Of Category)
    Get
    Private Set
'Usage
Dim instance As GetChannelCategoryHierarchyResponse
Dim value As ReadOnlyCollection(Of Category)

value = instance.ChannelCategories
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<Category> ChannelCategories { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<Category^>^ ChannelCategories {
    ReadOnlyCollection<Category^>^ get ();
    private: void set (ReadOnlyCollection<Category^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Category](category-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelCategoryHierarchyResponse Class](getchannelcategoryhierarchyresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

