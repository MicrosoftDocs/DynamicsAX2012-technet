---
title: Customer.EmailLogisticsLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmailLogisticsLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.EmailLogisticsLocationId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customer.emaillogisticslocationid(v=AX.60)
ms:contentKeyID: 62212443
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.EmailLogisticsLocationId
dev_langs:
- CSharp
- C++
- VB
---

# EmailLogisticsLocationId Property

Gets or sets the email logistics location id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EMAILLOCATIONID")> _
<IgnoreDataMemberAttribute> _
Public Property EmailLogisticsLocationId As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.EmailLogisticsLocationId

instance.EmailLogisticsLocationId = value
```

``` csharp
[ColumnAttribute("EMAILLOCATIONID")]
[IgnoreDataMemberAttribute]
public string EmailLogisticsLocationId { get; set; }
```

``` c++
[ColumnAttribute(L"EMAILLOCATIONID")]
[IgnoreDataMemberAttribute]
public:
property String^ EmailLogisticsLocationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The email logistics location id.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

