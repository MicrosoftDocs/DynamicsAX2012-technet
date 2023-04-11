---
title: TenderType.OperationName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OperationName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.OperationName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.operationname(v=AX.60)
ms:contentKeyID: 62211495
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.OperationName
dev_langs:
- CSharp
- C++
- VB
---

# OperationName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the operation name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OPERATIONNAME")> _
Public Property OperationName As String
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As String

value = instance.OperationName

instance.OperationName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OPERATIONNAME")]
public string OperationName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OPERATIONNAME")]
public:
property String^ OperationName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

