---
title: DeviceConfiguration.StatementPostingAsBusinessDay Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StatementPostingAsBusinessDay Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StatementPostingAsBusinessDay
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.statementpostingasbusinessday(v=AX.60)
ms:contentKeyID: 62214630
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StatementPostingAsBusinessDay
dev_langs:
- CSharp
- C++
- VB
---

# StatementPostingAsBusinessDay Property

Gets or sets a value indicating whether statement posting should use adjusted business day.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STATEMENTPOSTINGASBUSINESSDAY")> _
<IgnoreDataMemberAttribute> _
Public Property StatementPostingAsBusinessDay As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.StatementPostingAsBusinessDay

instance.StatementPostingAsBusinessDay = value
```

``` csharp
[ColumnAttribute("STATEMENTPOSTINGASBUSINESSDAY")]
[IgnoreDataMemberAttribute]
public bool StatementPostingAsBusinessDay { get; set; }
```

``` c++
[ColumnAttribute(L"STATEMENTPOSTINGASBUSINESSDAY")]
[IgnoreDataMemberAttribute]
public:
property bool StatementPostingAsBusinessDay {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

