---
title: ITransactionServicesV1.ExportStoreInventoryData Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: ExportStoreInventoryData Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.ExportStoreInventoryData(System.Boolean@,System.String@,System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv1.exportstoreinventorydata(v=AX.60)
ms:contentKeyID: 47129161
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV1.ExportStoreInventoryData
dev_langs:
- CSharp
- C++
- VB
---

# ExportStoreInventoryData Method

**Note: This API is now obsolete.**

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("The method is no longer supported. The AX side service API has been removed.")> _
Sub ExportStoreInventoryData ( _
    ByRef succeeded As Boolean, _
    ByRef comment As String, _
    command As String, _
    hhtId As String, _
    entryType As String, _
    exportParam As String _
)
'Usage
Dim instance As ITransactionServicesV1
Dim succeeded As Boolean
Dim comment As String
Dim command As String
Dim hhtId As String
Dim entryType As String
Dim exportParam As String

instance.ExportStoreInventoryData(succeeded, _
    comment, command, hhtId, entryType, _
    exportParam)
```

``` csharp
[ObsoleteAttribute("The method is no longer supported. The AX side service API has been removed.")]
void ExportStoreInventoryData(
    ref bool succeeded,
    ref string comment,
    string command,
    string hhtId,
    string entryType,
    string exportParam
)
```

``` c++
[ObsoleteAttribute(L"The method is no longer supported. The AX side service API has been removed.")]
void ExportStoreInventoryData(
    bool% succeeded, 
    String^% comment, 
    String^ command, 
    String^ hhtId, 
    String^ entryType, 
    String^ exportParam
)
```

#### Parameters

  - succeeded  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - command  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - hhtId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - entryType  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - exportParam  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ITransactionServicesV1 Interface](itransactionservicesv1-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

