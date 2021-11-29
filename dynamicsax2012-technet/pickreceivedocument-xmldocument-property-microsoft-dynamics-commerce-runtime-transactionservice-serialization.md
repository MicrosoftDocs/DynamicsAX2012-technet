---
title: PickReceiveDocument.XMLDocument Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: XMLDocument Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.PickReceiveDocument.XMLDocument
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.pickreceivedocument.xmldocument(v=AX.60)
ms:contentKeyID: 62209239
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.PickReceiveDocument.XMLDocument
dev_langs:
- CSharp
- C++
- VB
---

# XMLDocument Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the picking or receiving document as xml.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property XMLDocument As String
    Get
    Set
'Usage
Dim instance As PickReceiveDocument
Dim value As String

value = instance.XMLDocument

instance.XMLDocument = value
```

``` csharp
public string XMLDocument { get; set; }
```

``` c++
public:
property String^ XMLDocument {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PickReceiveDocument Class](pickreceivedocument-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

