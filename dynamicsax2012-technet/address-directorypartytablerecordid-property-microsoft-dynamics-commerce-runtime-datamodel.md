---
title: Address.DirectoryPartyTableRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DirectoryPartyTableRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.DirectoryPartyTableRecordId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.address.directorypartytablerecordid(v=AX.60)
ms:contentKeyID: 62213345
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.DirectoryPartyTableRecordId
dev_langs:
- CSharp
- C++
- VB
---

# DirectoryPartyTableRecordId Property

Gets or sets the record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DIRPARTYTABLERECID")> _
<ReadOnlyAttribute("DIRPARTYTABLERECID")> _
Public Property DirectoryPartyTableRecordId As Long
    Get
    Set
'Usage
Dim instance As Address
Dim value As Long

value = instance.DirectoryPartyTableRecordId

instance.DirectoryPartyTableRecordId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DIRPARTYTABLERECID")]
[ReadOnlyAttribute("DIRPARTYTABLERECID")]
public long DirectoryPartyTableRecordId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DIRPARTYTABLERECID")]
[ReadOnlyAttribute(L"DIRPARTYTABLERECID")]
public:
property long long DirectoryPartyTableRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
The record identifier.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

