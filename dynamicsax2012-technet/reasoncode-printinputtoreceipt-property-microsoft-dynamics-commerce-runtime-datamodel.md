---
title: ReasonCode.PrintInputToReceipt Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrintInputToReceipt Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.PrintInputToReceipt
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.printinputtoreceipt(v=AX.60)
ms:contentKeyID: 62209393
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.PrintInputToReceipt
dev_langs:
- CSharp
- C++
- VB
---

# PrintInputToReceipt Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether print input to receipt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRINTINPUTONRECEIPT")> _
<DataMemberAttribute> _
Public Property PrintInputToReceipt As Boolean
    Get
    Friend Set
'Usage
Dim instance As ReasonCode
Dim value As Boolean

value = instance.PrintInputToReceipt
```

``` csharp
[ColumnAttribute("PRINTINPUTONRECEIPT")]
[DataMemberAttribute]
public bool PrintInputToReceipt { get; internal set; }
```

``` c++
[ColumnAttribute(L"PRINTINPUTONRECEIPT")]
[DataMemberAttribute]
public:
property bool PrintInputToReceipt {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value true if print input to receipt; otherwise, false.  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

