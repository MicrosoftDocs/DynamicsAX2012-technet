---
title: DeviceConfiguration.VoidTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VoidTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.VoidTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.voidtransaction(v=AX.60)
ms:contentKeyID: 62208871
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.VoidTransaction
dev_langs:
- CSharp
- C++
- VB
---

# VoidTransaction Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the void transaction reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("VOIDTRANSACTION")> _
Public Property VoidTransaction As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.VoidTransaction

instance.VoidTransaction = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("VOIDTRANSACTION")]
public string VoidTransaction { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"VOIDTRANSACTION")]
public:
property String^ VoidTransaction {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the void transaction reason code.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

