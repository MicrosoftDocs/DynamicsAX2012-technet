---
title: PaymentCardBase.Country Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Country Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.Country
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcardbase.country(v=AX.60)
ms:contentKeyID: 65321464
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.Country
dev_langs:
- CSharp
- C++
- VB
---

# Country Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value for Country.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Country As String
    Get
    Set
'Usage
Dim instance As PaymentCardBase
Dim value As String

value = instance.Country

instance.Country = value
```

``` csharp
[DataMemberAttribute]
public string Country { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Country {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The country.  

## See Also

#### Reference

[PaymentCardBase Class](paymentcardbase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

