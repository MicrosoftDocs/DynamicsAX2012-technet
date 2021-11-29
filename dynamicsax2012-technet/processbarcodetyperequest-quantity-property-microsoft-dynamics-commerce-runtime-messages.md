---
title: ProcessBarcodeTypeRequest.Quantity Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Quantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ProcessBarcodeTypeRequest.Quantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.processbarcodetyperequest.quantity(v=AX.60)
ms:contentKeyID: 65322547
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ProcessBarcodeTypeRequest.Quantity
dev_langs:
- CSharp
- C++
- VB
---

# Quantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Quantity As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As ProcessBarcodeTypeRequest
Dim value As Nullable(Of Decimal)

value = instance.Quantity

instance.Quantity = value
```

``` csharp
[DataMemberAttribute]
public Nullable<decimal> Quantity { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<Decimal> Quantity {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\>  

## See Also

#### Reference

[ProcessBarcodeTypeRequest Class](processbarcodetyperequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

