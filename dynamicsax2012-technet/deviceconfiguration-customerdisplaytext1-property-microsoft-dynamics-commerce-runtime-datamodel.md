---
title: DeviceConfiguration.CustomerDisplayText1 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerDisplayText1 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.CustomerDisplayText1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.customerdisplaytext1(v=AX.60)
ms:contentKeyID: 62211620
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.CustomerDisplayText1
dev_langs:
- CSharp
- C++
- VB
---

# CustomerDisplayText1 Property

Gets or sets the customer display text 1.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CUSTOMERDISPLAYTEXT1")> _
<DataMemberAttribute> _
Public Property CustomerDisplayText1 As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.CustomerDisplayText1

instance.CustomerDisplayText1 = value
```

``` csharp
[ColumnAttribute("CUSTOMERDISPLAYTEXT1")]
[DataMemberAttribute]
public string CustomerDisplayText1 { get; set; }
```

``` c++
[ColumnAttribute(L"CUSTOMERDISPLAYTEXT1")]
[DataMemberAttribute]
public:
property String^ CustomerDisplayText1 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The string containing the customer display text.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

