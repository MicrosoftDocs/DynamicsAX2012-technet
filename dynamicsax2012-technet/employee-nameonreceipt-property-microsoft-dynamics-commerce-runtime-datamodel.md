---
title: Employee.NameOnReceipt Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NameOnReceipt Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee.NameOnReceipt
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employee.nameonreceipt(v=AX.60)
ms:contentKeyID: 62214352
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee.NameOnReceipt
dev_langs:
- CSharp
- C++
- VB
---

# NameOnReceipt Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the Name on the receipt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("NAMEONRECEIPT")> _
Public Property NameOnReceipt As String
    Get
    Set
'Usage
Dim instance As Employee
Dim value As String

value = instance.NameOnReceipt

instance.NameOnReceipt = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("NAMEONRECEIPT")]
public string NameOnReceipt { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"NAMEONRECEIPT")]
public:
property String^ NameOnReceipt {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The Name on the receipt.  

## See Also

#### Reference

[Employee Class](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

