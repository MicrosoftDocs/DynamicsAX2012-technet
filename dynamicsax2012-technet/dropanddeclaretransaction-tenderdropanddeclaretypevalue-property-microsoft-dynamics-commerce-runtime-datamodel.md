---
title: DropAndDeclareTransaction.TenderDropAndDeclareTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderDropAndDeclareTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction.TenderDropAndDeclareTypeValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.dropanddeclaretransaction.tenderdropanddeclaretypevalue(v=AX.60)
ms:contentKeyID: 62211630
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction.TenderDropAndDeclareTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# TenderDropAndDeclareTypeValue Property

Gets or sets the value of the TenderDropAndDeclareType enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderDropAndDeclareTypeValue As Integer
    Get
    Set
'Usage
Dim instance As DropAndDeclareTransaction
Dim value As Integer

value = instance.TenderDropAndDeclareTypeValue

instance.TenderDropAndDeclareTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int TenderDropAndDeclareTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int TenderDropAndDeclareTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[DropAndDeclareTransaction Class](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

