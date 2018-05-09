---
title: IPosTransactionV1.StorePhone Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: StorePhone Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.StorePhone
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv1.storephone(v=AX.60)
ms:contentKeyID: 47129158
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.StorePhone
dev_langs:
- CSharp
- C++
- VB
---

# StorePhone Property

Gets the store phone number.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property StorePhone As String
    Get
    Set
'Usage
Dim instance As IPosTransactionV1
Dim value As String

value = instance.StorePhone

instance.StorePhone = value
```

``` csharp
string StorePhone { get; set; }
```

``` c++
property String^ StorePhone {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IPosTransactionV1 Interface](ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

