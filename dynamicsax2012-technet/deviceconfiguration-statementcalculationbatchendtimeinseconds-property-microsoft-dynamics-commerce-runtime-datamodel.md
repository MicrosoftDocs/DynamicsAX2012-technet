---
title: DeviceConfiguration.StatementCalculationBatchEndTimeInSeconds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StatementCalculationBatchEndTimeInSeconds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StatementCalculationBatchEndTimeInSeconds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.statementcalculationbatchendtimeinseconds(v=AX.60)
ms:contentKeyID: 62208541
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StatementCalculationBatchEndTimeInSeconds
dev_langs:
- CSharp
- C++
- VB
---

# StatementCalculationBatchEndTimeInSeconds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the statement calculation batch end time in seconds.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STATEMENTCALCULATIONBATCHENDTIMEINSECONDS")> _
<IgnoreDataMemberAttribute> _
Public Property StatementCalculationBatchEndTimeInSeconds As Integer
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Integer

value = instance.StatementCalculationBatchEndTimeInSeconds

instance.StatementCalculationBatchEndTimeInSeconds = value
```

``` csharp
[ColumnAttribute("STATEMENTCALCULATIONBATCHENDTIMEINSECONDS")]
[IgnoreDataMemberAttribute]
public int StatementCalculationBatchEndTimeInSeconds { get; set; }
```

``` c++
[ColumnAttribute(L"STATEMENTCALCULATIONBATCHENDTIMEINSECONDS")]
[IgnoreDataMemberAttribute]
public:
property int StatementCalculationBatchEndTimeInSeconds {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

