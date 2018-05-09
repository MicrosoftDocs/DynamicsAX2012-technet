---
title: GetStoreOperationRequest.NonSalesTenderType Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: NonSalesTenderType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreOperationRequest.NonSalesTenderType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getstoreoperationrequest.nonsalestendertype(v=AX.60)
ms:contentKeyID: 62212864
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreOperationRequest.NonSalesTenderType
dev_langs:
- CSharp
- C++
- VB
---

# NonSalesTenderType Property

Gets or sets non sale tender type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property NonSalesTenderType As NonSalesTenderType
    Get
    Set
'Usage
Dim instance As GetStoreOperationRequest
Dim value As NonSalesTenderType

value = instance.NonSalesTenderType

instance.NonSalesTenderType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public NonSalesTenderType NonSalesTenderType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property NonSalesTenderType NonSalesTenderType {
    NonSalesTenderType get ();
    void set (NonSalesTenderType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTenderType](nonsalestendertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [NonSalesTenderType](nonsalestendertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetStoreOperationRequest Class](getstoreoperationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

