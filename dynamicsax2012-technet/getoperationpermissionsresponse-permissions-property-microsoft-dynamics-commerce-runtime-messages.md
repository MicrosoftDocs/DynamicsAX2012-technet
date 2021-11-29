---
title: GetOperationPermissionsResponse.Permissions Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Permissions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOperationPermissionsResponse.Permissions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getoperationpermissionsresponse.permissions(v=AX.60)
ms:contentKeyID: 62214437
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetOperationPermissionsResponse.Permissions
dev_langs:
- CSharp
- C++
- VB
---

# Permissions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of operation permission objects.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Permissions As ReadOnlyCollection(Of OperationPermission)
    Get
    Private Set
'Usage
Dim instance As GetOperationPermissionsResponse
Dim value As ReadOnlyCollection(Of OperationPermission)

value = instance.Permissions
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<OperationPermission> Permissions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<OperationPermission^>^ Permissions {
    ReadOnlyCollection<OperationPermission^>^ get ();
    private: void set (ReadOnlyCollection<OperationPermission^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OperationPermission](operationpermission-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetOperationPermissionsResponse Class](getoperationpermissionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

