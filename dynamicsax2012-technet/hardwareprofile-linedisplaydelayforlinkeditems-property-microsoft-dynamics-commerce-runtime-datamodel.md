---
title: HardwareProfile.LineDisplayDelayForLinkedItems Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDisplayDelayForLinkedItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayDelayForLinkedItems
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.linedisplaydelayforlinkeditems(v=AX.60)
ms:contentKeyID: 62214456
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayDelayForLinkedItems
dev_langs:
- CSharp
- C++
- VB
---

# LineDisplayDelayForLinkedItems Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the delay for linked items value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DELAYFORLINKEDITEMS")> _
<DataMemberAttribute> _
Public Property LineDisplayDelayForLinkedItems As Integer
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Integer

value = instance.LineDisplayDelayForLinkedItems

instance.LineDisplayDelayForLinkedItems = value
```

``` csharp
[ColumnAttribute("DELAYFORLINKEDITEMS")]
[DataMemberAttribute]
public int LineDisplayDelayForLinkedItems { get; set; }
```

``` c++
[ColumnAttribute(L"DELAYFORLINKEDITEMS")]
[DataMemberAttribute]
public:
property int LineDisplayDelayForLinkedItems {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The delay for linked items value.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

