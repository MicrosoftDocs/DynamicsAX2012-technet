---
title: CheckAccessRequest.CommercePrincipal Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CommercePrincipal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CheckAccessRequest.CommercePrincipal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.checkaccessrequest.commerceprincipal(v=AX.60)
ms:contentKeyID: 62215055
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CheckAccessRequest.CommercePrincipal
dev_langs:
- CSharp
- C++
- VB
---

# CommercePrincipal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the commerce principal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CommercePrincipal As CommercePrincipal
    Get
    Private Set
'Usage
Dim instance As CheckAccessRequest
Dim value As CommercePrincipal

value = instance.CommercePrincipal
```

``` csharp
[DataMemberAttribute]
public CommercePrincipal CommercePrincipal { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property CommercePrincipal^ CommercePrincipal {
    CommercePrincipal^ get ();
    private: void set (CommercePrincipal^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  
The commerce principal.  

## See Also

#### Reference

[CheckAccessRequest Class](checkaccessrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

