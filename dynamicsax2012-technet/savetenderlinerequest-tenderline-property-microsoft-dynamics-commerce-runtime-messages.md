---
title: SaveTenderLineRequest.TenderLine Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TenderLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTenderLineRequest.TenderLine
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.savetenderlinerequest.tenderline(v=AX.60)
ms:contentKeyID: 62213754
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTenderLineRequest.TenderLine
dev_langs:
- CSharp
- C++
- VB
---

# TenderLine Property

Gets or sets the tender line to be added to the cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderLine As CartTenderLine
    Get
    Set
'Usage
Dim instance As SaveTenderLineRequest
Dim value As CartTenderLine

value = instance.TenderLine

instance.TenderLine = value
```

``` csharp
[DataMemberAttribute]
public CartTenderLine TenderLine { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property CartTenderLine^ TenderLine {
    CartTenderLine^ get ();
    void set (CartTenderLine^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartTenderLine](carttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CartTenderLine](carttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SaveTenderLineRequest Class](savetenderlinerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

