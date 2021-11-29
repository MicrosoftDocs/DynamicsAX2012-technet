---
title: ChargeConfigurationHeader.AccountType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader.AccountType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfigurationheader.accounttype(v=AX.60)
ms:contentKeyID: 49822984
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader.AccountType
dev_langs:
- CSharp
- C++
- VB
---

# AccountType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets granularity of customer selection to search for (i.e. single, group, all).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property AccountType As ChargeAccountType
    Get
    Set
'Usage
Dim instance As ChargeConfigurationHeader
Dim value As ChargeAccountType

value = instance.AccountType

instance.AccountType = value
```

``` csharp
public ChargeAccountType AccountType { get; set; }
```

``` c++
public:
property ChargeAccountType AccountType {
    ChargeAccountType get ();
    void set (ChargeAccountType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeAccountType](chargeaccounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChargeAccountType](chargeaccounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChargeConfigurationHeader Class](chargeconfigurationheader-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

