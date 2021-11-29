---
title: IEFTInfoV1.ApplicationIdentifier Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ApplicationIdentifier Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.ApplicationIdentifier
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov1.applicationidentifier(v=AX.60)
ms:contentKeyID: 47129148
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV1.ApplicationIdentifier
dev_langs:
- CSharp
- C++
- VB
---

# ApplicationIdentifier Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the application identifier (AID).

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ApplicationIdentifier As String
    Get
    Set
'Usage
Dim instance As IEFTInfoV1
Dim value As String

value = instance.ApplicationIdentifier

instance.ApplicationIdentifier = value
```

``` csharp
string ApplicationIdentifier { get; set; }
```

``` c++
property String^ ApplicationIdentifier {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The application identifier.  

## See Also

#### Reference

[IEFTInfoV1 Interface](ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

