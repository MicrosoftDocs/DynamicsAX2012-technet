---
title: GetReceiptServiceRequest.NonSalesTenderTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: NonSalesTenderTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest.NonSalesTenderTransaction
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getreceiptservicerequest.nonsalestendertransaction(v=AX.60)
ms:contentKeyID: 62211107
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest.NonSalesTenderTransaction
dev_langs:
- CSharp
- C++
- VB
---

# NonSalesTenderTransaction Property

Gets or sets the non sale tender transaction if any.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NonSalesTenderTransaction As NonSalesTransaction
    Get
    Set
'Usage
Dim instance As GetReceiptServiceRequest
Dim value As NonSalesTransaction

value = instance.NonSalesTenderTransaction

instance.NonSalesTenderTransaction = value
```

``` csharp
[DataMemberAttribute]
public NonSalesTransaction NonSalesTenderTransaction { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property NonSalesTransaction^ NonSalesTenderTransaction {
    NonSalesTransaction^ get ();
    void set (NonSalesTransaction^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetReceiptServiceRequest Class](getreceiptservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

