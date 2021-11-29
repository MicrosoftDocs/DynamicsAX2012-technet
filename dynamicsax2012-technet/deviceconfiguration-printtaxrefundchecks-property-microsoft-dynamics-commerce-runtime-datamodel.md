---
title: DeviceConfiguration.PrintTaxRefundChecks Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrintTaxRefundChecks Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.PrintTaxRefundChecks
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.printtaxrefundchecks(v=AX.60)
ms:contentKeyID: 62211697
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.PrintTaxRefundChecks
dev_langs:
- CSharp
- C++
- VB
---

# PrintTaxRefundChecks Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether print tax refund checks is enabled.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRINTVATREFUNDCHECKS")> _
<DataMemberAttribute> _
Public Property PrintTaxRefundChecks As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.PrintTaxRefundChecks

instance.PrintTaxRefundChecks = value
```

``` csharp
[ColumnAttribute("PRINTVATREFUNDCHECKS")]
[DataMemberAttribute]
public bool PrintTaxRefundChecks { get; set; }
```

``` c++
[ColumnAttribute(L"PRINTVATREFUNDCHECKS")]
[DataMemberAttribute]
public:
property bool PrintTaxRefundChecks {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value true if print tax refund checks is enabled; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

