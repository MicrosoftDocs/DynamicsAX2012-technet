---
title: TransactionServiceProfile.StaffLogOnConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StaffLogOnConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.StaffLogOnConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transactionserviceprofile.stafflogonconfiguration(v=AX.60)
ms:contentKeyID: 62207885
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.StaffLogOnConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# StaffLogOnConfiguration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the staff log on configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TSSTAFFLOGONCONFIGURATION")> _
<IgnoreDataMemberAttribute> _
Public Property StaffLogOnConfiguration As LogOnConfiguration
    Get
    Set
'Usage
Dim instance As TransactionServiceProfile
Dim value As LogOnConfiguration

value = instance.StaffLogOnConfiguration

instance.StaffLogOnConfiguration = value
```

``` csharp
[ColumnAttribute("TSSTAFFLOGONCONFIGURATION")]
[IgnoreDataMemberAttribute]
public LogOnConfiguration StaffLogOnConfiguration { get; set; }
```

``` c++
[ColumnAttribute(L"TSSTAFFLOGONCONFIGURATION")]
[IgnoreDataMemberAttribute]
public:
property LogOnConfiguration StaffLogOnConfiguration {
    LogOnConfiguration get ();
    void set (LogOnConfiguration value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnConfiguration](logonconfiguration-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LogOnConfiguration](logonconfiguration-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[TransactionServiceProfile Class](transactionserviceprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

