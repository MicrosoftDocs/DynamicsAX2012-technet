---
title: SalesTransaction.ChargeLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ChargeLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.chargelines(v=AX.60)
ms:contentKeyID: 49838217
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ChargeLines
dev_langs:
- CSharp
- C++
- VB
---

# ChargeLines Property

Gets or sets the charge lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChargeLines As Collection(Of ChargeLine)
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Collection(Of ChargeLine)

value = instance.ChargeLines

instance.ChargeLines = value
```

``` csharp
[DataMemberAttribute]
public Collection<ChargeLine> ChargeLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<ChargeLine^>^ ChargeLines {
    Collection<ChargeLine^>^ get ();
    void set (Collection<ChargeLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[ChargeLine](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

