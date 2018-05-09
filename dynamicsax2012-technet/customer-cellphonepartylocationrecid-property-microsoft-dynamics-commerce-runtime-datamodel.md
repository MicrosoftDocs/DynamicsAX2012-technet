---
title: Customer.CellphonePartyLocationRecId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CellphonePartyLocationRecId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CellphonePartyLocationRecId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customer.cellphonepartylocationrecid(v=AX.60)
ms:contentKeyID: 62213916
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.CellphonePartyLocationRecId
dev_langs:
- CSharp
- C++
- VB
---

# CellphonePartyLocationRecId Property

Gets or sets the cellphone party location rec id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CELLPHONEPARTYLOCATIONRECORDID")> _
Public Property CellphonePartyLocationRecId As Long
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Long

value = instance.CellphonePartyLocationRecId

instance.CellphonePartyLocationRecId = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CELLPHONEPARTYLOCATIONRECORDID")]
public long CellphonePartyLocationRecId { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CELLPHONEPARTYLOCATIONRECORDID")]
public:
property long long CellphonePartyLocationRecId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
The cellphone party location rec id.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

