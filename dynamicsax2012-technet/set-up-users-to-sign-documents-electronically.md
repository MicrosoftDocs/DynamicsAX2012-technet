---
title: Set up users to sign documents electronically
TOCTitle: Set up users to sign documents electronically
ms:assetid: 4d1aff77-e1c9-40ca-b862-d7c30e1eb15d
ms:mtpsurl: https://technet.microsoft.com/library/Dd309673(v=AX.60)
ms:contentKeyID: 36057025
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- compliance
- e-signature
audience: Application User
ms.search.region: Global
---

# Set up users to sign documents electronically 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To sign documents electronically, a user must meet the following criteria:

  - A user must belong to a role that is assigned the appropriate privileges.

  - A user must have a valid certificate and password. For information about certificates, see [Certificates for electronic signatures](certificates-for-electronic-signatures.md).

Three kinds of users typically require security access to electronic signatures: electronic signature administrators, signers, and electronic signature auditors.

## Electronic signature administrator

The electronic signature administrator sets up signature requirements, general parameters, and approvers, and receives alerts when signatures cannot be verified. By default, a user who belongs to the **Information technology manager** security role has permission to administer electronic signatures.

## Signer

A signer provides electronic signatures for documents and processes that require signatures. By default, a user who belongs to the **System user** security role has permission to sign documents electronically.


> [!NOTE]
> <P>The signer may require additional permissions to access data that is related to the document or process that is being signed. A user who changes data, and then must sign for those changes, must have permission to change the data. A user who signs on behalf of another user may not require access to the data. An example of this kind of user is a supervisor who signs for an employee's changes.</P>



## Electronic signature auditor

The electronic signature auditor reviews the database log and the signature review log that is available from the database log. By default, a user who belongs to the **Information technology manager** security role has permission to audit electronic signatures.

If you use a role other than **Information technology manager**, make sure that the role is assigned the following privileges:

  - **View electronic signature failures**

  - **View database log**

For more information, see [Create or modify a security role](create-or-modify-a-security-role.md).

  


