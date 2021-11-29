---
title: GetProductCatalogsRequest.ActiveOnly Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ActiveOnly Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductCatalogsRequest.ActiveOnly
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getproductcatalogsrequest.activeonly(v=AX.60)
ms:contentKeyID: 62207266
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductCatalogsRequest.ActiveOnly
dev_langs:
- CSharp
- C++
- VB
---

# ActiveOnly Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the catalogs must be active.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ActiveOnly As Boolean
    Get
    Set
'Usage
Dim instance As GetProductCatalogsRequest
Dim value As Boolean

value = instance.ActiveOnly

instance.ActiveOnly = value
```

``` csharp
[DataMemberAttribute]
public bool ActiveOnly { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool ActiveOnly {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetProductCatalogsRequest Class](getproductcatalogsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

