---
title: GetChannelCategoryHierarchyResponse.Name Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Name Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryHierarchyResponse.Name
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelcategoryhierarchyresponse.name(v=AX.60)
ms:contentKeyID: 49837925
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryHierarchyResponse.Name
dev_langs:
- CSharp
- C++
- VB
---

# Name Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel category hierarchy name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Name As String
    Get
    Private Set
'Usage
Dim instance As GetChannelCategoryHierarchyResponse
Dim value As String

value = instance.Name
```

``` csharp
[DataMemberAttribute]
public string Name { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Name {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelCategoryHierarchyResponse Class](getchannelcategoryhierarchyresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

