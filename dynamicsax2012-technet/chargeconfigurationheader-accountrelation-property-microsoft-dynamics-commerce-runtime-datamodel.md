---
title: ChargeConfigurationHeader.AccountRelation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccountRelation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader.AccountRelation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfigurationheader.accountrelation(v=AX.60)
ms:contentKeyID: 49833427
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader.AccountRelation
dev_langs:
- CSharp
- C++
- VB
---

# AccountRelation Property

Gets or sets the customer identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property AccountRelation As String
    Get
    Set
'Usage
Dim instance As ChargeConfigurationHeader
Dim value As String

value = instance.AccountRelation

instance.AccountRelation = value
```

``` csharp
public string AccountRelation { get; set; }
```

``` c++
public:
property String^ AccountRelation {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

This value can be account number, charge group id, or blank (for all AccountTypes, respectively).

## See Also

#### Reference

[ChargeConfigurationHeader Class](chargeconfigurationheader-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

