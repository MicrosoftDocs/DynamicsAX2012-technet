---
title: ReasonCode.RetailUseReasonCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RetailUseReasonCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.RetailUseReasonCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.retailusereasoncode(v=AX.60)
ms:contentKeyID: 62211098
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.RetailUseReasonCode
dev_langs:
- CSharp
- C++
- VB
---

# RetailUseReasonCode Property

Gets a value indicating whether retail use reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RETAILUSEINFOCODE")> _
Public Property RetailUseReasonCode As Boolean
    Get
    Friend Set
'Usage
Dim instance As ReasonCode
Dim value As Boolean

value = instance.RetailUseReasonCode
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RETAILUSEINFOCODE")]
public bool RetailUseReasonCode { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RETAILUSEINFOCODE")]
public:
property bool RetailUseReasonCode {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if retail use reason code; otherwise, false.  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

