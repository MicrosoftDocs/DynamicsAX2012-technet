---
title: CartLine.ReturnTransactionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnTransactionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.ReturnTransactionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.returntransactionid(v=AX.60)
ms:contentKeyID: 62210200
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.ReturnTransactionId
dev_langs:
- CSharp
- C++
- VB
---

# ReturnTransactionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the returned transaction identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReturnTransactionId As String
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As String

value = instance.ReturnTransactionId

instance.ReturnTransactionId = value
```

``` csharp
[DataMemberAttribute]
public string ReturnTransactionId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReturnTransactionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The transaction identifier.  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

