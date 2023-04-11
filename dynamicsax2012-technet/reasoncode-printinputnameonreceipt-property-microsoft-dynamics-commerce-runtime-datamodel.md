---
title: ReasonCode.PrintInputNameOnReceipt Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrintInputNameOnReceipt Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.PrintInputNameOnReceipt
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.printinputnameonreceipt(v=AX.60)
ms:contentKeyID: 62214202
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.PrintInputNameOnReceipt
dev_langs:
- CSharp
- C++
- VB
---

# PrintInputNameOnReceipt Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether print input name on receipt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRINTINPUTNAMEONRECEIPT")> _
Public Property PrintInputNameOnReceipt As Boolean
    Get
    Friend Set
'Usage
Dim instance As ReasonCode
Dim value As Boolean

value = instance.PrintInputNameOnReceipt
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRINTINPUTNAMEONRECEIPT")]
public bool PrintInputNameOnReceipt { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRINTINPUTNAMEONRECEIPT")]
public:
property bool PrintInputNameOnReceipt {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value true if print input name on receipt; otherwise, false.  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

