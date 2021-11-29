---
title: DeviceConfiguration.ExitAfterEachTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExitAfterEachTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.ExitAfterEachTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.exitaftereachtransaction(v=AX.60)
ms:contentKeyID: 62213549
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.ExitAfterEachTransaction
dev_langs:
- CSharp
- C++
- VB
---

# ExitAfterEachTransaction Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether exit after each transaction is enabled.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EXITAFTEREACHTRANSACTION")> _
Public Property ExitAfterEachTransaction As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.ExitAfterEachTransaction

instance.ExitAfterEachTransaction = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EXITAFTEREACHTRANSACTION")]
public bool ExitAfterEachTransaction { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EXITAFTEREACHTRANSACTION")]
public:
property bool ExitAfterEachTransaction {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value true if exit after each transaction is enabled; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

