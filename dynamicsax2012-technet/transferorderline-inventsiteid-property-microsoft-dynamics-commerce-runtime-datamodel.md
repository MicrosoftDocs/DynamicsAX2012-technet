---
title: TransferOrderLine.InventSiteId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventSiteId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.InventSiteId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.transferorderline.inventsiteid(v=AX.60)
ms:contentKeyID: 62214617
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.InventSiteId
dev_langs:
- CSharp
- C++
- VB
---

# InventSiteId Property

Gets or sets the inventory site identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTSITEID")> _
<DataMemberAttribute> _
Public Property InventSiteId As String
    Get
    Set
'Usage
Dim instance As TransferOrderLine
Dim value As String

value = instance.InventSiteId

instance.InventSiteId = value
```

``` csharp
[ColumnAttribute("INVENTSITEID")]
[DataMemberAttribute]
public string InventSiteId { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTSITEID")]
[DataMemberAttribute]
public:
property String^ InventSiteId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TransferOrderLine Class](transferorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

