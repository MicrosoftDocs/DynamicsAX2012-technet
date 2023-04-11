---
title: SaveReasonCodeLineRequest.ParentLineId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ParentLineId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveReasonCodeLineRequest.ParentLineId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savereasoncodelinerequest.parentlineid(v=AX.60)
ms:contentKeyID: 62212871
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveReasonCodeLineRequest.ParentLineId
dev_langs:
- CSharp
- C++
- VB
---

# ParentLineId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the parent line ID.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ParentLineId As String
    Get
    Set
'Usage
Dim instance As SaveReasonCodeLineRequest
Dim value As String

value = instance.ParentLineId

instance.ParentLineId = value
```

``` csharp
[DataMemberAttribute]
public string ParentLineId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ParentLineId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SaveReasonCodeLineRequest Class](savereasoncodelinerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

