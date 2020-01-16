---
title: ReasonCodeSettings.DefaultSettings Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DefaultSettings Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSettings.DefaultSettings
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodesettings.defaultsettings(v=AX.60)
ms:contentKeyID: 62213733
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSettings.DefaultSettings
dev_langs:
- CSharp
- C++
- VB
---

# DefaultSettings Property

Gets the default settings (no reason code set).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared ReadOnly Property DefaultSettings As ReasonCodeSettings
    Get
'Usage
Dim value As ReasonCodeSettings

value = ReasonCodeSettings.DefaultSettings
```

``` csharp
public static ReasonCodeSettings DefaultSettings { get; }
```

``` c++
public:
static property ReasonCodeSettings^ DefaultSettings {
    ReasonCodeSettings^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSettings](reasoncodesettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The default settings.  

## See Also

#### Reference

[ReasonCodeSettings Class](reasoncodesettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

