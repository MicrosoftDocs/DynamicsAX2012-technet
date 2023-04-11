---
title: DeviceConfiguration.RetentionDays Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RetentionDays Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.RetentionDays
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.retentiondays(v=AX.60)
ms:contentKeyID: 65315468
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.RetentionDays
dev_langs:
- CSharp
- C++
- VB
---

# RetentionDays Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DAYSTRANSACTIONSEXISTS")> _
Public Property RetentionDays As Integer
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Integer

value = instance.RetentionDays

instance.RetentionDays = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DAYSTRANSACTIONSEXISTS")]
public int RetentionDays { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DAYSTRANSACTIONSEXISTS")]
public:
property int RetentionDays {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

