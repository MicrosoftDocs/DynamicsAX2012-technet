---
title: IDatabaseResult.GetValue Method (String, Type) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetValue Method (String, Type)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult.GetValue(System.String,System.Type)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatabaseresult.getvalue(v=AX.60)
ms:contentKeyID: 65318157
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetValue Method (String, Type)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the value for a specific field in the current result set row.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetValue ( _
    fieldName As String, _
    valueType As Type _
) As Object
'Usage
Dim instance As IDatabaseResult
Dim fieldName As String
Dim valueType As Type
Dim returnValue As Object

returnValue = instance.GetValue(fieldName, _
    valueType)
```

``` csharp
Object GetValue(
    string fieldName,
    Type valueType
)
```

``` c++
Object^ GetValue(
    String^ fieldName, 
    Type^ valueType
)
```

#### Parameters

  - fieldName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - valueType  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

#### Return Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
The field value read.  

## See Also

#### Reference

[IDatabaseResult Interface](idatabaseresult-interface-microsoft-dynamics-commerce-runtime-data.md)

[GetValue Overload](idatabaseresult-getvalue-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

