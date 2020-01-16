---
title: EndReadChangedProductsRequest.Session Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Session Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.EndReadChangedProductsRequest.Session
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.endreadchangedproductsrequest.session(v=AX.60)
ms:contentKeyID: 62210960
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.EndReadChangedProductsRequest.Session
dev_langs:
- CSharp
- C++
- VB
---

# Session Property

Gets or sets session.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property Session As ReadChangedProductsSession
    Get
    Set
'Usage
Dim instance As EndReadChangedProductsRequest
Dim value As ReadChangedProductsSession

value = instance.Session

instance.Session = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public ReadChangedProductsSession Session { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property ReadChangedProductsSession^ Session {
    ReadChangedProductsSession^ get ();
    void set (ReadChangedProductsSession^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession](readchangedproductssession-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ReadChangedProductsSession](readchangedproductssession-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[EndReadChangedProductsRequest Class](endreadchangedproductsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

