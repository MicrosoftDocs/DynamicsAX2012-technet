---
title: Currency.NumberOfDecimals Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NumberOfDecimals Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency.NumberOfDecimals
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.currency.numberofdecimals(v=AX.60)
ms:contentKeyID: 62210005
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency.NumberOfDecimals
dev_langs:
- CSharp
- C++
- VB
---

# NumberOfDecimals Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the Numbe Of Decimals of Round off Sales.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NumberOfDecimals As Short
    Get
    Set
'Usage
Dim instance As Currency
Dim value As Short

value = instance.NumberOfDecimals

instance.NumberOfDecimals = value
```

``` csharp
[DataMemberAttribute]
public short NumberOfDecimals { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property short NumberOfDecimals {
    short get ();
    void set (short value);
}
```

#### Property Value

Type: [System.Int16](https://technet.microsoft.com/library/e07e6fds\(v=ax.60\))  
Returns [Int16](https://technet.microsoft.com/library/e07e6fds\(v=ax.60\)).  

## See Also

#### Reference

[Currency Class](currency-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

