---
title: VersionElement.Value Property  (Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration.VersionElement.Value
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.configuration.versionelement.value(v=AX.60)
ms:contentKeyID: 62203486
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration.VersionElement.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the service version value.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration](microsoft-dynamics-retail-retailserverlibrary-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("value", DefaultValue := "V1")> _
Public ReadOnly Property Value As String
    Get
'Usage
Dim instance As VersionElement
Dim value As String

value = instance.Value
```

``` csharp
[ConfigurationPropertyAttribute("value", DefaultValue = "V1")]
public string Value { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"value", DefaultValue = L"V1")]
public:
property String^ Value {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[VersionElement Class](versionelement-class-microsoft-dynamics-retail-retailserverlibrary-configuration.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration Namespace](microsoft-dynamics-retail-retailserverlibrary-configuration-namespace.md)

