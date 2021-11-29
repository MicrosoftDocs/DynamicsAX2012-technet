---
title: DeviceConfiguration.CustomerDisplayText2 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerDisplayText2 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.CustomerDisplayText2
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.customerdisplaytext2(v=AX.60)
ms:contentKeyID: 62205536
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.CustomerDisplayText2
dev_langs:
- CSharp
- C++
- VB
---

# CustomerDisplayText2 Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer display text 2.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CUSTOMERDISPLAYTEXT2")> _
<DataMemberAttribute> _
Public Property CustomerDisplayText2 As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.CustomerDisplayText2

instance.CustomerDisplayText2 = value
```

``` csharp
[ColumnAttribute("CUSTOMERDISPLAYTEXT2")]
[DataMemberAttribute]
public string CustomerDisplayText2 { get; set; }
```

``` c++
[ColumnAttribute(L"CUSTOMERDISPLAYTEXT2")]
[DataMemberAttribute]
public:
property String^ CustomerDisplayText2 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the customer display text.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

