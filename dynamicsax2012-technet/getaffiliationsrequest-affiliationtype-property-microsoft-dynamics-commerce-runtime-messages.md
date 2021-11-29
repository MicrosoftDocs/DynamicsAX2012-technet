---
title: GetAffiliationsRequest.AffiliationType Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: AffiliationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAffiliationsRequest.AffiliationType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaffiliationsrequest.affiliationtype(v=AX.60)
ms:contentKeyID: 62214953
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAffiliationsRequest.AffiliationType
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the affiliation type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AffiliationType As Integer
    Get
    Set
'Usage
Dim instance As GetAffiliationsRequest
Dim value As Integer

value = instance.AffiliationType

instance.AffiliationType = value
```

``` csharp
[DataMemberAttribute]
public int AffiliationType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int AffiliationType {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[GetAffiliationsRequest Class](getaffiliationsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

