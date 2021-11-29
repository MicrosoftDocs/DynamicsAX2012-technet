---
title: Receipt.Footer Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Footer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Receipt.Footer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receipt.footer(v=AX.60)
ms:contentKeyID: 62211822
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Receipt.Footer
dev_langs:
- CSharp
- C++
- VB
---

# Footer Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the footer of the receipt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Footer As String
    Get
    Set
'Usage
Dim instance As Receipt
Dim value As String

value = instance.Footer

instance.Footer = value
```

``` csharp
[DataMemberAttribute]
public string Footer { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Footer {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Receipt Class](receipt-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

