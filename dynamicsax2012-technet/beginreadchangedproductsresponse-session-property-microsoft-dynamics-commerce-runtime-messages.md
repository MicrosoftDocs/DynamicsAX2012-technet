---
title: BeginReadChangedProductsResponse.Session Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Session Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.BeginReadChangedProductsResponse.Session
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.beginreadchangedproductsresponse.session(v=AX.60)
ms:contentKeyID: 62213743
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.BeginReadChangedProductsResponse.Session
dev_langs:
- CSharp
- C++
- VB
---

# Session Property

Gets session.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Session As ReadChangedProductsSession
    Get
    Private Set
'Usage
Dim instance As BeginReadChangedProductsResponse
Dim value As ReadChangedProductsSession

value = instance.Session
```

``` csharp
[DataMemberAttribute]
public ReadChangedProductsSession Session { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadChangedProductsSession^ Session {
    ReadChangedProductsSession^ get ();
    private: void set (ReadChangedProductsSession^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession](readchangedproductssession-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ReadChangedProductsSession](readchangedproductssession-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[BeginReadChangedProductsResponse Class](beginreadchangedproductsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

