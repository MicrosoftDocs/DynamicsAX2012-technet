---
title: Barcode.EmployeeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmployeeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.EmployeeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.employeeid(v=AX.60)
ms:contentKeyID: 62210842
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.EmployeeId
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeId Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EmployeeId As String
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As String

value = instance.EmployeeId

instance.EmployeeId = value
```

``` csharp
[DataMemberAttribute]
public string EmployeeId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ EmployeeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

