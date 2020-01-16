---
title: GetPriceAndDiscountDataServiceRequest.CustomerAccount Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CustomerAccount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.CustomerAccount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpriceanddiscountdataservicerequest.customeraccount(v=AX.60)
ms:contentKeyID: 65322397
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.CustomerAccount
dev_langs:
- CSharp
- C++
- VB
---

# CustomerAccount Property

Gets or sets the customer account.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerAccount As String
    Get
    Protected Set
'Usage
Dim instance As GetPriceAndDiscountDataServiceRequest
Dim value As String

value = instance.CustomerAccount

instance.CustomerAccount = value
```

``` csharp
[DataMemberAttribute]
public string CustomerAccount { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CustomerAccount {
    String^ get ();
    protected: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetPriceAndDiscountDataServiceRequest Class](getpriceanddiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

