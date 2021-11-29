---
title: GetLineDeliveryOptionsRequest.SalesLines Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SalesLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetLineDeliveryOptionsRequest.SalesLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getlinedeliveryoptionsrequest.saleslines(v=AX.60)
ms:contentKeyID: 62212370
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetLineDeliveryOptionsRequest.SalesLines
dev_langs:
- CSharp
- C++
- VB
---

# SalesLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesLines As IEnumerable(Of SalesLine)
    Get
    Set
'Usage
Dim instance As GetLineDeliveryOptionsRequest
Dim value As IEnumerable(Of SalesLine)

value = instance.SalesLines

instance.SalesLines = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<SalesLine> SalesLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<SalesLine^>^ SalesLines {
    IEnumerable<SalesLine^>^ get ();
    void set (IEnumerable<SalesLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetLineDeliveryOptionsRequest Class](getlinedeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

