---
title: ICommerceRuntimeConfiguration.ConnectionString Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ConnectionString Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration.ConnectionString
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.icommerceruntimeconfiguration.connectionstring(v=AX.60)
ms:contentKeyID: 65319911
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration.ConnectionString
dev_langs:
- CSharp
- C++
- VB
---

# ConnectionString Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the connection string to the database that contains the storage lookup view.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Property ConnectionString As String
    Get
    Set
'Usage
Dim instance As ICommerceRuntimeConfiguration
Dim value As String

value = instance.ConnectionString

instance.ConnectionString = value
```

``` csharp
string ConnectionString { get; set; }
```

``` c++
property String^ ConnectionString {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

If [IsConnectionStringOverridden](icommerceruntimeconfiguration-isconnectionstringoverridden-property-microsoft-dynamics-commerce-runtime.md) is set to true, then storage resolution is not attempted.

## See Also

#### Reference

[ICommerceRuntimeConfiguration Interface](icommerceruntimeconfiguration-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

