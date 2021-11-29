---
title: GetShipmentLineMappingRequest.SalesIdCollection Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SalesIdCollection Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentLineMappingRequest.SalesIdCollection
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getshipmentlinemappingrequest.salesidcollection(v=AX.60)
ms:contentKeyID: 62212577
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentLineMappingRequest.SalesIdCollection
dev_langs:
- CSharp
- C++
- VB
---

# SalesIdCollection Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales id collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property SalesIdCollection As IEnumerable(Of String)
    Get
    Set
'Usage
Dim instance As GetShipmentLineMappingRequest
Dim value As IEnumerable(Of String)

value = instance.SalesIdCollection

instance.SalesIdCollection = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public IEnumerable<string> SalesIdCollection { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property IEnumerable<String^>^ SalesIdCollection {
    IEnumerable<String^>^ get ();
    void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
The sales id collection.  

## See Also

#### Reference

[GetShipmentLineMappingRequest Class](getshipmentlinemappingrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

