---
title: GetSalesTaxGroupsResponse.SalesTaxGroups Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SalesTaxGroups Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetSalesTaxGroupsResponse.SalesTaxGroups
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getsalestaxgroupsresponse.salestaxgroups(v=AX.60)
ms:contentKeyID: 62212776
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetSalesTaxGroupsResponse.SalesTaxGroups
dev_langs:
- CSharp
- C++
- VB
---

# SalesTaxGroups Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales tax groups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesTaxGroups As ReadOnlyCollection(Of SalesTaxGroup)
    Get
    Private Set
'Usage
Dim instance As GetSalesTaxGroupsResponse
Dim value As ReadOnlyCollection(Of SalesTaxGroup)

value = instance.SalesTaxGroups
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<SalesTaxGroup> SalesTaxGroups { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<SalesTaxGroup^>^ SalesTaxGroups {
    ReadOnlyCollection<SalesTaxGroup^>^ get ();
    private: void set (ReadOnlyCollection<SalesTaxGroup^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesTaxGroup](salestaxgroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The sales tax groups.  

## See Also

#### Reference

[GetSalesTaxGroupsResponse Class](getsalestaxgroupsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

