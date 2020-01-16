---
title: DeviceConfiguration.VoidPayment Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VoidPayment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.VoidPayment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.voidpayment(v=AX.60)
ms:contentKeyID: 62204406
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.VoidPayment
dev_langs:
- CSharp
- C++
- VB
---

# VoidPayment Property

Gets or sets the void payment reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VOIDPAYMENT")> _
<DataMemberAttribute> _
Public Property VoidPayment As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.VoidPayment

instance.VoidPayment = value
```

``` csharp
[ColumnAttribute("VOIDPAYMENT")]
[DataMemberAttribute]
public string VoidPayment { get; set; }
```

``` c++
[ColumnAttribute(L"VOIDPAYMENT")]
[DataMemberAttribute]
public:
property String^ VoidPayment {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the void payment reason code.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

