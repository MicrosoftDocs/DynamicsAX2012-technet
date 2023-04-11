---
title: DeleteStockCountRequest.InventStyleId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: InventStyleId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteStockCountRequest.InventStyleId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.deletestockcountrequest.inventstyleid(v=AX.60)
ms:contentKeyID: 62208396
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteStockCountRequest.InventStyleId
dev_langs:
- CSharp
- C++
- VB
---

# InventStyleId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the invent style identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventStyleId As String
    Get
    Private Set
'Usage
Dim instance As DeleteStockCountRequest
Dim value As String

value = instance.InventStyleId
```

``` csharp
[DataMemberAttribute]
public string InventStyleId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InventStyleId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DeleteStockCountRequest Class](deletestockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

