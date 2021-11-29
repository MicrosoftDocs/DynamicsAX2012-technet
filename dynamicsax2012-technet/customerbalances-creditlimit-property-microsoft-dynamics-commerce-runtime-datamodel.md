---
title: CustomerBalances.CreditLimit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CreditLimit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerBalances.CreditLimit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customerbalances.creditlimit(v=AX.60)
ms:contentKeyID: 62207902
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerBalances.CreditLimit
dev_langs:
- CSharp
- C++
- VB
---

# CreditLimit Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property CreditLimit As Decimal
    Get
    Set
'Usage
Dim instance As CustomerBalances
Dim value As Decimal

value = instance.CreditLimit

instance.CreditLimit = value
```

``` csharp
public decimal CreditLimit { get; set; }
```

``` c++
public:
property Decimal CreditLimit {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[CustomerBalances Class](customerbalances-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

