---
title: DeviceConfiguration.NewOfflineDatabaseCheckInterval Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NewOfflineDatabaseCheckInterval Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.NewOfflineDatabaseCheckInterval
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.newofflinedatabasecheckinterval(v=AX.60)
ms:contentKeyID: 65321140
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.NewOfflineDatabaseCheckInterval
dev_langs:
- CSharp
- C++
- VB
---

# NewOfflineDatabaseCheckInterval Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CHECKNEWDBINTERVAL")> _
Public Property NewOfflineDatabaseCheckInterval As Integer
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Integer

value = instance.NewOfflineDatabaseCheckInterval

instance.NewOfflineDatabaseCheckInterval = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CHECKNEWDBINTERVAL")]
public int NewOfflineDatabaseCheckInterval { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CHECKNEWDBINTERVAL")]
public:
property int NewOfflineDatabaseCheckInterval {
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

