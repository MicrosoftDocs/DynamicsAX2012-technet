---
title: ProductRefinerValue.RefinerRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RefinerRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.RefinerRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrefinervalue.refinerrecordid(v=AX.60)
ms:contentKeyID: 65321744
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.RefinerRecordId
dev_langs:
- CSharp
- C++
- VB
---

# RefinerRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RECID")> _
<KeyAttribute> _
<DataMemberAttribute> _
Public Property RefinerRecordId As Long
    Get
    Set
'Usage
Dim instance As ProductRefinerValue
Dim value As Long

value = instance.RefinerRecordId

instance.RefinerRecordId = value
```

``` csharp
[ColumnAttribute("RECID")]
[KeyAttribute]
[DataMemberAttribute]
public long RefinerRecordId { get; set; }
```

``` c++
[ColumnAttribute(L"RECID")]
[KeyAttribute]
[DataMemberAttribute]
public:
property long long RefinerRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The record identifier.  

## See Also

#### Reference

[ProductRefinerValue Class](productrefinervalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

