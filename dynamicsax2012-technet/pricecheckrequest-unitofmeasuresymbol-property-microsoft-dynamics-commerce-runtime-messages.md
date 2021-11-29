---
title: PriceCheckRequest.UnitOfMeasureSymbol Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: UnitOfMeasureSymbol Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckRequest.UnitOfMeasureSymbol
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.pricecheckrequest.unitofmeasuresymbol(v=AX.60)
ms:contentKeyID: 62209120
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckRequest.UnitOfMeasureSymbol
dev_langs:
- CSharp
- C++
- VB
---

# UnitOfMeasureSymbol Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the unit of measure symbol.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UnitOfMeasureSymbol As String
    Get
    Private Set
'Usage
Dim instance As PriceCheckRequest
Dim value As String

value = instance.UnitOfMeasureSymbol
```

``` csharp
[DataMemberAttribute]
public string UnitOfMeasureSymbol { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ UnitOfMeasureSymbol {
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

