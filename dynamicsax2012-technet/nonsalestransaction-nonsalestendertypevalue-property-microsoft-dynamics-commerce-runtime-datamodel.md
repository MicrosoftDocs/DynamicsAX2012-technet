---
title: NonSalesTransaction.NonSalesTenderTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NonSalesTenderTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction.NonSalesTenderTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.nonsalestransaction.nonsalestendertypevalue(v=AX.60)
ms:contentKeyID: 62212067
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction.NonSalesTenderTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# NonSalesTenderTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the NonSalesTenderType enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NonSalesTenderTypeValue As Integer
    Get
    Set
'Usage
Dim instance As NonSalesTransaction
Dim value As Integer

value = instance.NonSalesTenderTypeValue

instance.NonSalesTenderTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int NonSalesTenderTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int NonSalesTenderTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[NonSalesTransaction Class](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

