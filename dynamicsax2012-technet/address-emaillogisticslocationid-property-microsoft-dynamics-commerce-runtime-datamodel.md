---
title: Address.EmailLogisticsLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmailLogisticsLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.EmailLogisticsLocationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.emaillogisticslocationid(v=AX.60)
ms:contentKeyID: 62208795
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.EmailLogisticsLocationId
dev_langs:
- CSharp
- C++
- VB
---

# EmailLogisticsLocationId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the email logistics location id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EMAILLOCATIONID")> _
<DataMemberAttribute> _
<ReadOnlyAttribute("EMAILLOCATIONID")> _
Public Property EmailLogisticsLocationId As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.EmailLogisticsLocationId

instance.EmailLogisticsLocationId = value
```

``` csharp
[ColumnAttribute("EMAILLOCATIONID")]
[DataMemberAttribute]
[ReadOnlyAttribute("EMAILLOCATIONID")]
public string EmailLogisticsLocationId { get; set; }
```

``` c++
[ColumnAttribute(L"EMAILLOCATIONID")]
[DataMemberAttribute]
[ReadOnlyAttribute(L"EMAILLOCATIONID")]
public:
property String^ EmailLogisticsLocationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The email logistics location id.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

