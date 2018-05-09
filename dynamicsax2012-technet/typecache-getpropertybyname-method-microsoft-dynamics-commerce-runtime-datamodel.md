---
title: TypeCache.GetPropertyByName Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetPropertyByName Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCache.GetPropertyByName(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.typecache.getpropertybyname(v=AX.60)
ms:contentKeyID: 65317729
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCache.GetPropertyByName
dev_langs:
- CSharp
- C++
- VB
---

# GetPropertyByName Method

Get [PropertyInfo](https://technet.microsoft.com/en-us/library/8z852kf5\(v=ax.60\)) by name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function GetPropertyByName ( _
    name As String _
) As PropertyInfo
'Usage
Dim instance As TypeCache
Dim name As String
Dim returnValue As PropertyInfo

returnValue = instance.GetPropertyByName(name)
```

``` csharp
public PropertyInfo GetPropertyByName(
    string name
)
```

``` c++
public:
PropertyInfo^ GetPropertyByName(
    String^ name
)
```

#### Parameters

  - name  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Reflection.PropertyInfo](https://technet.microsoft.com/en-us/library/8z852kf5\(v=ax.60\))  
Instance of [PropertyInfo](https://technet.microsoft.com/en-us/library/8z852kf5\(v=ax.60\)) or null if not found.  

## See Also

#### Reference

[TypeCache Class](typecache-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

