---
title: DeviceConfiguration.TenderDeclarationCalculation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderDeclarationCalculation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.TenderDeclarationCalculation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.tenderdeclarationcalculation(v=AX.60)
ms:contentKeyID: 62204787
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.TenderDeclarationCalculation
dev_langs:
- CSharp
- C++
- VB
---

# TenderDeclarationCalculation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tender declaration calculation value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TENDERDECLARATIONCALCULATION")> _
Public Property TenderDeclarationCalculation As Integer
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Integer

value = instance.TenderDeclarationCalculation

instance.TenderDeclarationCalculation = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TENDERDECLARATIONCALCULATION")]
public int TenderDeclarationCalculation { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TENDERDECLARATIONCALCULATION")]
public:
property int TenderDeclarationCalculation {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The tender declaration calculation value.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

