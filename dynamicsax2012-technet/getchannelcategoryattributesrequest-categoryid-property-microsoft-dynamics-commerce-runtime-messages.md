---
title: GetChannelCategoryAttributesRequest.CategoryId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CategoryId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryAttributesRequest.CategoryId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getchannelcategoryattributesrequest.categoryid(v=AX.60)
ms:contentKeyID: 49850757
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryAttributesRequest.CategoryId
dev_langs:
- CSharp
- C++
- VB
---

# CategoryId Property

Gets or sets the category identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CategoryId As Long
    Get
    Set
'Usage
Dim instance As GetChannelCategoryAttributesRequest
Dim value As Long

value = instance.CategoryId

instance.CategoryId = value
```

``` csharp
[DataMemberAttribute]
public long CategoryId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long CategoryId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
The category identifier.  

## See Also

#### Reference

[GetChannelCategoryAttributesRequest Class](getchannelcategoryattributesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

