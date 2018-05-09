---
title: Preauthorization.PaymentPropertiesBlob Property  (Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder)
TOCTitle: PaymentPropertiesBlob Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.Preauthorization.PaymentPropertiesBlob
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.customerorder.preauthorization.paymentpropertiesblob(v=AX.60)
ms:contentKeyID: 62213596
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder.Preauthorization.PaymentPropertiesBlob
dev_langs:
- CSharp
- C++
- VB
---

# PaymentPropertiesBlob Property

Gets or sets the Payment SDK properties XML.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property PaymentPropertiesBlob As String
    Get
    Set
'Usage
Dim instance As Preauthorization
Dim value As String

value = instance.PaymentPropertiesBlob

instance.PaymentPropertiesBlob = value
```

``` csharp
public string PaymentPropertiesBlob { get; set; }
```

``` c++
public:
property String^ PaymentPropertiesBlob {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Preauthorization Class](preauthorization-class-microsoft-dynamics-commerce-runtime-services-customerorder.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.CustomerOrder Namespace](microsoft-dynamics-commerce-runtime-services-customerorder-namespace.md)

