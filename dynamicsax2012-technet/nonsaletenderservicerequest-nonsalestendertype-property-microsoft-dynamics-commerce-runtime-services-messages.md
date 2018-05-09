---
title: NonSaleTenderServiceRequest.NonSalesTenderType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: NonSalesTenderType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.NonSaleTenderServiceRequest.NonSalesTenderType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.nonsaletenderservicerequest.nonsalestendertype(v=AX.60)
ms:contentKeyID: 62212702
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.NonSaleTenderServiceRequest.NonSalesTenderType
dev_langs:
- CSharp
- C++
- VB
---

# NonSalesTenderType Property

Gets or sets the drawer entry transaction type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NonSalesTenderType As NonSalesTenderType
    Get
    Set
'Usage
Dim instance As NonSaleTenderServiceRequest
Dim value As NonSalesTenderType

value = instance.NonSalesTenderType

instance.NonSalesTenderType = value
```

``` csharp
[DataMemberAttribute]
public NonSalesTenderType NonSalesTenderType { get; set; }
```

``` c++
[DataMemberAttribute]
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

[NonSaleTenderServiceRequest Class](nonsaletenderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

