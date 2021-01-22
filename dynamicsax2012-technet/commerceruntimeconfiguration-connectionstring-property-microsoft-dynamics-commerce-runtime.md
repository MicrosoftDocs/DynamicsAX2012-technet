---
title: CommerceRuntimeConfiguration.ConnectionString Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ConnectionString Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.ConnectionString
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntimeconfiguration.connectionstring(v=AX.60)
ms:contentKeyID: 49854030
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.ConnectionString
dev_langs:
- CSharp
- C++
- VB
---

# ConnectionString Property

Gets the connection string to the database that contains the storage lookup view.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Property ConnectionString As String
    Get
    Set
'Usage
Dim instance As CommerceRuntimeConfiguration
Dim value As String

value = instance.ConnectionString

instance.ConnectionString = value
```

``` csharp
public string ConnectionString { get; set; }
```

``` c++
public:
virtual property String^ ConnectionString {
    String^ get () sealed;
    void set (String^ value) sealed;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

#### Implements

[ICommerceRuntimeConfiguration.ConnectionString](icommerceruntimeconfiguration-connectionstring-property-microsoft-dynamics-commerce-runtime.md)  

## Remarks

If [IsConnectionStringOverridden](commerceruntimeconfiguration-isconnectionstringoverridden-property-microsoft-dynamics-commerce-runtime.md) is set to true, then storage resolution is not attempted.

## See Also

#### Reference

[CommerceRuntimeConfiguration Class](commerceruntimeconfiguration-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

