---
title: DeleteStockCountRequest.InventSizeId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: InventSizeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteStockCountRequest.InventSizeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.deletestockcountrequest.inventsizeid(v=AX.60)
ms:contentKeyID: 62213224
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteStockCountRequest.InventSizeId
dev_langs:
- CSharp
- C++
- VB
---

# InventSizeId Property

Gets the invent size identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventSizeId As String
    Get
    Private Set
'Usage
Dim instance As DeleteStockCountRequest
Dim value As String

value = instance.InventSizeId
```

``` csharp
[DataMemberAttribute]
public string InventSizeId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InventSizeId {
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

