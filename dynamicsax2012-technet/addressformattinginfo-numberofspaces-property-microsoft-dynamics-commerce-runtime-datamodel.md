---
title: AddressFormattingInfo.NumberOfSpaces Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NumberOfSpaces Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.NumberOfSpaces
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.addressformattinginfo.numberofspaces(v=AX.60)
ms:contentKeyID: 65317198
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.NumberOfSpaces
dev_langs:
- CSharp
- C++
- VB
---

# NumberOfSpaces Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("NUMOFSPACES")> _
Public Property NumberOfSpaces As Integer
    Get
    Set
'Usage
Dim instance As AddressFormattingInfo
Dim value As Integer

value = instance.NumberOfSpaces

instance.NumberOfSpaces = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("NUMOFSPACES")]
public int NumberOfSpaces { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"NUMOFSPACES")]
public:
property int NumberOfSpaces {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[AddressFormattingInfo Class](addressformattinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

