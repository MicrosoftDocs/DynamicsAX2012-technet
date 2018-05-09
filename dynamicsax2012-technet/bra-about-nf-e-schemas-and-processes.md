---
title: (BRA) About NF-e schemas and processes
TOCTitle: (BRA) About NF-e schemas and processes
ms:assetid: f2cdd223-2f5c-4f7a-9892-4c42d8d87781
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ898463(v=AX.60)
ms:contentKeyID: 50873682
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- electronic fiscal document layout
- electronic fiscal document schema
- NF-e layout
- NF-e schema
- BR - 00021
- BR - 00007
---

# (BRA) About NF-e schemas and processes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can generate a nota fiscal eletrônica (NF-e) to register the movement of items and services between two parties. After you generate an NF-e, the NF-e export or import process detects the posted fiscal document and generates XML messages according to the fiscal document processes, which are submitted to the Secretaria da Fazenda (SEFAZ). You can set up the NF-e schema that is used to validate the XML message in the **NF-e federal parameters** form. For more information, see “Set up an NF-e schema” in [(BRA) Set up NF-e federal parameters](bra-set-up-nf-e-federal-parameters.md).

## NF-e process

During the NF-e process, the XML messages are generated depending on the status of the NF-e, as follows:

  - **Send NF-e** – This XML message type is used to send an NF-e that is posted by using the NF-e federal fiscal document type.

  - **Send NF-e Cancellation** – This XML message type is used to send a cancellation of an NF-e that is generated when you cancel an **Approved** NF-e.

  - **Send Discarded Number** – This XML message type is used to send a discarded NF-e number that is generated when you reverse a **Created**, **Rejected**, or **Rejected non fixable** NF-e.

  - **Return NF-e** – This XML message type is used to receive a returned message for an NF-e from SEFAZ.

  - **Return NF-e Cancellation** – This XML message type is used to receive a returned message for a canceled NF-e from SEFAZ.

  - **Return Discarded Number** – This XML message type is used to receive a return message for a discarded NF-e from SEFAZ.

  - **Send Inquiry NF-e status** – This XML message type is used to inquire about the status of an NF-e that was sent to SEFAZ.

  - **Return Inquiry NF-e status** – This XML message type is used to receive the status of the NF-e from SEFAZ.

## See also

[(BRA) Configure a digital certificate for an NF-e](bra-configure-a-digital-certificate-for-an-nf-e.md)

[(BRA) About the NF-e process](bra-about-the-nf-e-process.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

