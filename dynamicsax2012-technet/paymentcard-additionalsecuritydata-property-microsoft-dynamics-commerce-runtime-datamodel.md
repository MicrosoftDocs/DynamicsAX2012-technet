---
title: PaymentCard.AdditionalSecurityData Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AdditionalSecurityData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard.AdditionalSecurityData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcard.additionalsecuritydata(v=AX.60)
ms:contentKeyID: 62211683
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard.AdditionalSecurityData
dev_langs:
- CSharp
- C++
- VB
---

# AdditionalSecurityData Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets additional security data for debit cards.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AdditionalSecurityData As String
    Get
    Set
'Usage
Dim instance As PaymentCard
Dim value As String

value = instance.AdditionalSecurityData

instance.AdditionalSecurityData = value
```

``` csharp
[DataMemberAttribute]
public string AdditionalSecurityData { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ AdditionalSecurityData {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PaymentCard Class](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

