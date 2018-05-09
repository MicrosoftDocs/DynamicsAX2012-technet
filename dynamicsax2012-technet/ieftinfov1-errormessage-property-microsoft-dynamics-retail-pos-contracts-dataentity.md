---
title: IEFTInfoV1.ErrorMessage Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ErrorMessage Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.ErrorMessage
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.errormessage(v=AX.60)
ms:contentKeyID: 47129353
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.ErrorMessage
dev_langs:
- CSharp
- C++
- VB
---

# ErrorMessage Property

The detailed error message for an EFT failure.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ErrorMessage As String
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As String

value = instance.ErrorMessage

instance.ErrorMessage = value
```

``` csharp
string ErrorMessage { get; set; }
```

``` c++
property String^ ErrorMessage {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IEFTInfoV1 Interface](ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

