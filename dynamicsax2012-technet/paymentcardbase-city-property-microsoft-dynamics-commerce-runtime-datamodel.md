---
title: PaymentCardBase.City Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: City Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.City
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcardbase.city(v=AX.60)
ms:contentKeyID: 65318391
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.City
dev_langs:
- CSharp
- C++
- VB
---

# City Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value for City.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property City As String
    Get
    Set
'Usage
Dim instance As PaymentCardBase
Dim value As String

value = instance.City

instance.City = value
```

``` csharp
[DataMemberAttribute]
public string City { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ City {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The city.  

## See Also

#### Reference

[PaymentCardBase Class](paymentcardbase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

