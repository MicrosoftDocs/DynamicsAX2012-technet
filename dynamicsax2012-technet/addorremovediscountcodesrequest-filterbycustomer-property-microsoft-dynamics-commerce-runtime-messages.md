---
title: AddOrRemoveDiscountCodesRequest.FilterByCustomer Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: FilterByCustomer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.AddOrRemoveDiscountCodesRequest.FilterByCustomer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.addorremovediscountcodesrequest.filterbycustomer(v=AX.60)
ms:contentKeyID: 65321943
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.AddOrRemoveDiscountCodesRequest.FilterByCustomer
dev_langs:
- CSharp
- C++
- VB
---

# FilterByCustomer Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property FilterByCustomer As Boolean
    Get
    Private Set
'Usage
Dim instance As AddOrRemoveDiscountCodesRequest
Dim value As Boolean

value = instance.FilterByCustomer
```

``` csharp
[DataMemberAttribute]
public bool FilterByCustomer { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool FilterByCustomer {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[AddOrRemoveDiscountCodesRequest Class](addorremovediscountcodesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

