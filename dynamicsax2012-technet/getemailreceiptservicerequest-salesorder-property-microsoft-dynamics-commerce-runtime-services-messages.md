---
title: GetEmailReceiptServiceRequest.SalesOrder Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SalesOrder Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmailReceiptServiceRequest.SalesOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getemailreceiptservicerequest.salesorder(v=AX.60)
ms:contentKeyID: 62210955
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmailReceiptServiceRequest.SalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrder Property

Gets or sets the sales order or the object that contains all the receipt data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesOrder As SalesOrder
    Get
    Set
'Usage
Dim instance As GetEmailReceiptServiceRequest
Dim value As SalesOrder

value = instance.SalesOrder

instance.SalesOrder = value
```

``` csharp
[DataMemberAttribute]
public SalesOrder SalesOrder { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property SalesOrder^ SalesOrder {
    SalesOrder^ get ();
    void set (SalesOrder^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetEmailReceiptServiceRequest Class](getemailreceiptservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

