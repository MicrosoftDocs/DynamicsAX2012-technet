---
title: PriceCheckRequest.Barcode Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Barcode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckRequest.Barcode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.pricecheckrequest.barcode(v=AX.60)
ms:contentKeyID: 62213561
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckRequest.Barcode
dev_langs:
- CSharp
- C++
- VB
---

# Barcode Property

Gets the barcode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Barcode As String
    Get
    Private Set
'Usage
Dim instance As PriceCheckRequest
Dim value As String

value = instance.Barcode
```

``` csharp
[DataMemberAttribute]
public string Barcode { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Barcode {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PriceCheckRequest Class](pricecheckrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

