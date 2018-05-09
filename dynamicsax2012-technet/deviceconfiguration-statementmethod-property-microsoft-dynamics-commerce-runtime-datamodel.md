---
title: DeviceConfiguration.StatementMethod Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StatementMethod Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StatementMethod
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.statementmethod(v=AX.60)
ms:contentKeyID: 62214711
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StatementMethod
dev_langs:
- CSharp
- C++
- VB
---

# StatementMethod Property

Gets or sets the statement methods value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("STATEMENTMETHOD")> _
Public Property StatementMethod As StatementMethod
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As StatementMethod

value = instance.StatementMethod

instance.StatementMethod = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("STATEMENTMETHOD")]
public StatementMethod StatementMethod { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"STATEMENTMETHOD")]
public:
property StatementMethod StatementMethod {
    StatementMethod get ();
    void set (StatementMethod value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StatementMethod](statementmethod-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The StatementMethods value.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

