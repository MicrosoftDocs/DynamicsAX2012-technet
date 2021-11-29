---
title: DeviceConfiguration.CultureName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CultureName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.CultureName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.culturename(v=AX.60)
ms:contentKeyID: 62209960
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.CultureName
dev_langs:
- CSharp
- C++
- VB
---

# CultureName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the culture name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CULTURENAME")> _
Public Property CultureName As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.CultureName

instance.CultureName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CULTURENAME")]
public string CultureName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CULTURENAME")]
public:
property String^ CultureName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the culture name.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

