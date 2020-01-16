---
title: ConnectionManager.ConnectionString Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ConnectionString Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager.ConnectionString
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.connectionmanager.connectionstring(v=AX.60)
ms:contentKeyID: 65318921
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager.ConnectionString
dev_langs:
- CSharp
- C++
- VB
---

# ConnectionString Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Property ConnectionString As String
    Get
    Private Set
'Usage
Dim instance As ConnectionManager
Dim value As String

value = instance.ConnectionString
```

``` csharp
public string ConnectionString { get; private set; }
```

``` c++
public:
property String^ ConnectionString {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ConnectionManager Class](connectionmanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

