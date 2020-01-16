---
title: OperationPermission.Permissions Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Permissions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OperationPermission.Permissions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.operationpermission.permissions(v=AX.60)
ms:contentKeyID: 62209624
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OperationPermission.Permissions
dev_langs:
- CSharp
- C++
- VB
---

# Permissions Property

Gets or sets the Permissions for the operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property Permissions As ReadOnlyCollection(Of String)
    Get
    Set
'Usage
Dim instance As OperationPermission
Dim value As ReadOnlyCollection(Of String)

value = instance.Permissions

instance.Permissions = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public ReadOnlyCollection<string> Permissions { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property ReadOnlyCollection<String^>^ Permissions {
    ReadOnlyCollection<String^>^ get ();
    void set (ReadOnlyCollection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Gets the Permissions value.  

## See Also

#### Reference

[OperationPermission Class](operationpermission-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

