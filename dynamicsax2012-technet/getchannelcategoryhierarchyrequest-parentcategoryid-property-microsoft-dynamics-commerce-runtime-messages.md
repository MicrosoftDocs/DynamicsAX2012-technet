---
title: GetChannelCategoryHierarchyRequest.ParentCategoryId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ParentCategoryId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryHierarchyRequest.ParentCategoryId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelcategoryhierarchyrequest.parentcategoryid(v=AX.60)
ms:contentKeyID: 62207905
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryHierarchyRequest.ParentCategoryId
dev_langs:
- CSharp
- C++
- VB
---

# ParentCategoryId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the parent category identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ParentCategoryId As Long
    Get
    Set
'Usage
Dim instance As GetChannelCategoryHierarchyRequest
Dim value As Long

value = instance.ParentCategoryId

instance.ParentCategoryId = value
```

``` csharp
[DataMemberAttribute]
public long ParentCategoryId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long ParentCategoryId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The category identifier of the parent category.  

## See Also

#### Reference

[GetChannelCategoryHierarchyRequest Class](getchannelcategoryhierarchyrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

