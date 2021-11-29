---
title: Employee.Image Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Image Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee.Image
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employee.image(v=AX.60)
ms:contentKeyID: 62204328
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee.Image
dev_langs:
- CSharp
- C++
- VB
---

# Image Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the image.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Image As RichMediaLocations
    Get
    Set
'Usage
Dim instance As Employee
Dim value As RichMediaLocations

value = instance.Image

instance.Image = value
```

``` csharp
[DataMemberAttribute]
public RichMediaLocations Image { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property RichMediaLocations^ Image {
    RichMediaLocations^ get ();
    void set (RichMediaLocations^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RichMediaLocations](richmedialocations-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The image.  

## See Also

#### Reference

[Employee Class](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

