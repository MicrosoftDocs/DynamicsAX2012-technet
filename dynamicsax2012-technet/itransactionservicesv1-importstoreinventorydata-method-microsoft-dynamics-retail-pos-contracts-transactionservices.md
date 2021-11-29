---
title: ITransactionServicesV1.ImportStoreInventoryData Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: ImportStoreInventoryData Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.ImportStoreInventoryData(System.Boolean@,System.String@,System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.importstoreinventorydata(v=AX.60)
ms:contentKeyID: 47128485
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.ImportStoreInventoryData
dev_langs:
- CSharp
- C++
- VB
---

# ImportStoreInventoryData Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Note: This API is now obsolete.**

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("The method is no longer supported. The AX side service API has been removed.")> _
Sub ImportStoreInventoryData ( _
    ByRef succeeded As Boolean, _
    ByRef comment As String, _
    command As String, _
    hhtId As String, _
    entryType As String, _
    importValue As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim succeeded As Boolean
Dim comment As String
Dim command As String
Dim hhtId As String
Dim entryType As String
Dim importValue As String

instance.ImportStoreInventoryData(succeeded, _
    comment, command, hhtId, entryType, _
    importValue)
```

``` csharp
[ObsoleteAttribute("The method is no longer supported. The AX side service API has been removed.")]
void ImportStoreInventoryData(
    ref bool succeeded,
    ref string comment,
    string command,
    string hhtId,
    string entryType,
    string importValue
)
```

``` c++
[ObsoleteAttribute(L"The method is no longer supported. The AX side service API has been removed.")]
void ImportStoreInventoryData(
    bool% succeeded, 
    String^% comment, 
    String^ command, 
    String^ hhtId, 
    String^ entryType, 
    String^ importValue
)
```

#### Parameters

  - succeeded  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - command  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - hhtId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - entryType  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - importValue  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

