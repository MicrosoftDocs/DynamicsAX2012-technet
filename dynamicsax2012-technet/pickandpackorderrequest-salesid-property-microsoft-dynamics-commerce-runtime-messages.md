---
title: PickAndPackOrderRequest.SalesId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SalesId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.PickAndPackOrderRequest.SalesId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.pickandpackorderrequest.salesid(v=AX.60)
ms:contentKeyID: 62210676
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.PickAndPackOrderRequest.SalesId
dev_langs:
- CSharp
- C++
- VB
---

# SalesId Property

Gets the cart identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property SalesId As String
    Get
    Private Set
'Usage
Dim instance As PickAndPackOrderRequest
Dim value As String

value = instance.SalesId
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public string SalesId { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property String^ SalesId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PickAndPackOrderRequest Class](pickandpackorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

