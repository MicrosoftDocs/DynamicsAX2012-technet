---
title: SalesTransaction.LineDiscountCalculationType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDiscountCalculationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.LineDiscountCalculationType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.linediscountcalculationtype(v=AX.60)
ms:contentKeyID: 49827854
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.LineDiscountCalculationType
dev_langs:
- CSharp
- C++
- VB
---

# LineDiscountCalculationType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets how the line discount is found/calculated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property LineDiscountCalculationType As LineDiscountCalculationType
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As LineDiscountCalculationType

value = instance.LineDiscountCalculationType

instance.LineDiscountCalculationType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public LineDiscountCalculationType LineDiscountCalculationType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property LineDiscountCalculationType LineDiscountCalculationType {
    LineDiscountCalculationType get ();
    void set (LineDiscountCalculationType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDiscountCalculationType](linediscountcalculationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LineDiscountCalculationType](linediscountcalculationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

