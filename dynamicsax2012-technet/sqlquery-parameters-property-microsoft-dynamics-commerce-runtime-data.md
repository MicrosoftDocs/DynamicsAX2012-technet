---
title: SqlQuery.Parameters Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Parameters Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.SqlQuery.Parameters
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlquery.parameters(v=AX.60)
ms:contentKeyID: 65322572
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SqlQuery.Parameters
dev_langs:
- CSharp
- C++
- VB
---

# Parameters Property

Gets the parameters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Property Parameters As IDictionary(Of String, Object)
    Get
    Private Set
'Usage
Dim instance As SqlQuery
Dim value As IDictionary(Of String, Object)

value = instance.Parameters
```

``` csharp
public IDictionary<string, Object> Parameters { get; private set; }
```

``` c++
public:
virtual property IDictionary<String^, Object^>^ Parameters {
    IDictionary<String^, Object^>^ get () sealed;
    private: void set (IDictionary<String^, Object^>^ value) sealed;
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>  
The parameters.  

#### Implements

[IDatabaseQuery.Parameters](idatabasequery-parameters-property-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[SqlQuery Class](sqlquery-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

