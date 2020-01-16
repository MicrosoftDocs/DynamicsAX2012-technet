---
title: SaveCartDataRequest.IgnoreRowVersionCheck Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: IgnoreRowVersionCheck Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveCartDataRequest.IgnoreRowVersionCheck
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.savecartdatarequest.ignorerowversioncheck(v=AX.60)
ms:contentKeyID: 65318858
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveCartDataRequest.IgnoreRowVersionCheck
dev_langs:
- CSharp
- C++
- VB
---

# IgnoreRowVersionCheck Property

Gets a value indicating whether the row version need to be checked.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property IgnoreRowVersionCheck As Boolean
    Get
    Private Set
'Usage
Dim instance As SaveCartDataRequest
Dim value As Boolean

value = instance.IgnoreRowVersionCheck
```

``` csharp
public bool IgnoreRowVersionCheck { get; private set; }
```

``` c++
public:
property bool IgnoreRowVersionCheck {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SaveCartDataRequest Class](savecartdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

