---
title: GetCartRequest.FilterByCustomer Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: FilterByCustomer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCartRequest.FilterByCustomer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcartrequest.filterbycustomer(v=AX.60)
ms:contentKeyID: 62212829
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCartRequest.FilterByCustomer
dev_langs:
- CSharp
- C++
- VB
---

# FilterByCustomer Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether to filter results by CustomerAccountNumber.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property FilterByCustomer As Boolean
    Get
    Set
'Usage
Dim instance As GetCartRequest
Dim value As Boolean

value = instance.FilterByCustomer

instance.FilterByCustomer = value
```

``` csharp
[DataMemberAttribute]
public bool FilterByCustomer { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool FilterByCustomer {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetCartRequest Class](getcartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

