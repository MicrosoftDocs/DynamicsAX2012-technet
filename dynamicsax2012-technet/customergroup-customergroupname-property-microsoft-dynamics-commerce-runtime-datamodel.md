---
title: CustomerGroup.CustomerGroupName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerGroupName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerGroup.CustomerGroupName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customergroup.customergroupname(v=AX.60)
ms:contentKeyID: 62201774
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerGroup.CustomerGroupName
dev_langs:
- CSharp
- C++
- VB
---

# CustomerGroupName Property

Gets or sets the customer group name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NAME")> _
<DataMemberAttribute> _
Public Property CustomerGroupName As String
    Get
    Set
'Usage
Dim instance As CustomerGroup
Dim value As String

value = instance.CustomerGroupName

instance.CustomerGroupName = value
```

``` csharp
[ColumnAttribute("NAME")]
[DataMemberAttribute]
public string CustomerGroupName { get; set; }
```

``` c++
[ColumnAttribute(L"NAME")]
[DataMemberAttribute]
public:
property String^ CustomerGroupName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CustomerGroup Class](customergroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

