---
title: GetCommerceListRequest.Id Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Id Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCommerceListRequest.Id
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getcommercelistrequest.id(v=AX.60)
ms:contentKeyID: 62214773
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCommerceListRequest.Id
dev_langs:
- CSharp
- C++
- VB
---

# Id Property

Gets or sets the commerce list identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Id As String
    Get
    Set
'Usage
Dim instance As GetCommerceListRequest
Dim value As String

value = instance.Id

instance.Id = value
```

``` csharp
[DataMemberAttribute]
public string Id { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Id {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

If commerce list identifier is not set, it will get all the commerce lists given a customer identifier.

## See Also

#### Reference

[GetCommerceListRequest Class](getcommercelistrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

