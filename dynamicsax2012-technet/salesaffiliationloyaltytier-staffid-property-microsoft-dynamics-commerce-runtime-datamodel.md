---
title: SalesAffiliationLoyaltyTier.StaffId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StaffId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesAffiliationLoyaltyTier.StaffId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesaffiliationloyaltytier.staffid(v=AX.60)
ms:contentKeyID: 62214989
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesAffiliationLoyaltyTier.StaffId
dev_langs:
- CSharp
- C++
- VB
---

# StaffId Property

Gets or sets the staff identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("STAFFID")> _
Public Property StaffId As String
    Get
    Set
'Usage
Dim instance As SalesAffiliationLoyaltyTier
Dim value As String

value = instance.StaffId

instance.StaffId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("STAFFID")]
public string StaffId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"STAFFID")]
public:
property String^ StaffId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SalesAffiliationLoyaltyTier Class](salesaffiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

