---
title: Payment.CardNumber Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: CardNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Payment.CardNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.payment.cardnumber(v=AX.60)
ms:contentKeyID: 65316582
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Payment.CardNumber
dev_langs:
- CSharp
- C++
- VB
---

# CardNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardNumber As String
    Get
    Set
'Usage
Dim instance As Payment
Dim value As String

value = instance.CardNumber

instance.CardNumber = value
```

``` csharp
[DataMemberAttribute]
public string CardNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CardNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Payment Class](payment-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

