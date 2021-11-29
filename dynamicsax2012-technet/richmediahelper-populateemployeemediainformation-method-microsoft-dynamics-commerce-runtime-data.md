---
title: RichMediaHelper.PopulateEmployeeMediaInformation Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PopulateEmployeeMediaInformation Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.RichMediaHelper.PopulateEmployeeMediaInformation(Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.richmediahelper.populateemployeemediainformation(v=AX.60)
ms:contentKeyID: 65321944
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.RichMediaHelper.PopulateEmployeeMediaInformation
dev_langs:
- CSharp
- C++
- VB
---

# PopulateEmployeeMediaInformation Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Populates the employee media information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function PopulateEmployeeMediaInformation ( _
    employee As Employee, _
    mediaBlob As String, _
    defaultValue As String _
) As RichMediaLocations
'Usage
Dim employee As Employee
Dim mediaBlob As String
Dim defaultValue As String
Dim returnValue As RichMediaLocations

returnValue = RichMediaHelper.PopulateEmployeeMediaInformation(employee, _
    mediaBlob, defaultValue)
```

``` csharp
public static RichMediaLocations PopulateEmployeeMediaInformation(
    Employee employee,
    string mediaBlob,
    string defaultValue
)
```

``` c++
public:
static RichMediaLocations^ PopulateEmployeeMediaInformation(
    Employee^ employee, 
    String^ mediaBlob, 
    String^ defaultValue
)
```

#### Parameters

  - employee  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - mediaBlob  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - defaultValue  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RichMediaLocations](richmedialocations-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
RichMediaLocations object.  

## See Also

#### Reference

[RichMediaHelper Class](richmediahelper-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

