---
title: IInfoCodeLineItemV1.PrintInputOnReceipt Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PrintInputOnReceipt Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.PrintInputOnReceipt
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iinfocodelineitemv1.printinputonreceipt(v=AX.60)
ms:contentKeyID: 49835997
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.PrintInputOnReceipt
dev_langs:
- CSharp
- C++
- VB
---

# PrintInputOnReceipt Property

Print what is inputed on the receipt

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PrintInputOnReceipt As Boolean
    Get
    Set
'Usage
Dim instance As IInfoCodeLineItemV1
Dim value As Boolean

value = instance.PrintInputOnReceipt

instance.PrintInputOnReceipt = value
```

``` csharp
bool PrintInputOnReceipt { get; set; }
```

``` c++
property bool PrintInputOnReceipt {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IInfoCodeLineItemV1 Interface](iinfocodelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

