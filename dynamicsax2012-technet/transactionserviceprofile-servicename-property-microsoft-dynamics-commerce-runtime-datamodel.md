---
title: TransactionServiceProfile.ServiceName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ServiceName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.ServiceName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transactionserviceprofile.servicename(v=AX.60)
ms:contentKeyID: 62214303
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile.ServiceName
dev_langs:
- CSharp
- C++
- VB
---

# ServiceName Property

Gets the name of the transaction service service.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TSSERVICENAME")> _
<IgnoreDataMemberAttribute> _
Public ReadOnly Property ServiceName As String
    Get
'Usage
Dim instance As TransactionServiceProfile
Dim value As String

value = instance.ServiceName
```

``` csharp
[ColumnAttribute("TSSERVICENAME")]
[IgnoreDataMemberAttribute]
public string ServiceName { get; }
```

``` c++
[ColumnAttribute(L"TSSERVICENAME")]
[IgnoreDataMemberAttribute]
public:
property String^ ServiceName {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TransactionServiceProfile Class](transactionserviceprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

