---
title: Channel.OrgUnitTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrgUnitTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.OrgUnitTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channel.orgunittypevalue(v=AX.60)
ms:contentKeyID: 62210627
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.OrgUnitTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# OrgUnitTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the value of the Type enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrgUnitTypeValue As Integer
    Get
    Friend Set
'Usage
Dim instance As Channel
Dim value As Integer

value = instance.OrgUnitTypeValue
```

``` csharp
[DataMemberAttribute]
public int OrgUnitTypeValue { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property int OrgUnitTypeValue {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Channel Class](channel-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

