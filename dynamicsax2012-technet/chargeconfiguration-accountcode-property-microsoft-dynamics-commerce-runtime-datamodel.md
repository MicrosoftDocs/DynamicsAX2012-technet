---
title: ChargeConfiguration.AccountCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccountCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.AccountCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfiguration.accountcode(v=AX.60)
ms:contentKeyID: 49842717
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.AccountCode
dev_langs:
- CSharp
- C++
- VB
---

# AccountCode Property

Gets or sets the type of customer for the configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ACCOUNTCODE")> _
<DataMemberAttribute> _
Public Property AccountCode As ChargeAccountType
    Get
    Set
'Usage
Dim instance As ChargeConfiguration
Dim value As ChargeAccountType

value = instance.AccountCode

instance.AccountCode = value
```

``` csharp
[ColumnAttribute("ACCOUNTCODE")]
[DataMemberAttribute]
public ChargeAccountType AccountCode { get; set; }
```

``` c++
[ColumnAttribute(L"ACCOUNTCODE")]
[DataMemberAttribute]
public:
property ChargeAccountType AccountCode {
    ChargeAccountType get ();
    void set (ChargeAccountType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeAccountType](chargeaccounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChargeAccountType](chargeaccounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChargeConfiguration Class](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

