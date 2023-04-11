---
title: (BRA) Set up NF-e federal parameters
TOCTitle: (BRA) Set up NF-e federal parameters
ms:assetid: 45298749-f4bb-4cb9-8696-87687243a37a
ms:mtpsurl: https://technet.microsoft.com/library/JJ933512(v=AX.60)
ms:contentKeyID: 50935128
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- electronic fiscal document parameters
- Forms.EFDocParameters_BR
- NF-e federal parameters
- BR-00044
- MsDynAx060.Forms.EFDocParameters_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up NF-e federal parameters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up Nota Fiscal eletrônica (NF-e) web services, rejection codes, and schema to generate an NF-e. After you generate an NF-e, XML messages are generated and submitted to the Secretaria da Fazenda (SEFAZ).

Use the following procedures to set up NF-e federal parameters.

## Set up web services for an NF-e

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **NF-e federal parameters**.

2.  In the **Web services** area, in the **Authorities** grid, click **New**.

3.  In the **Authority** field, enter the identification code of the agency that receives, approves, or rejects NF-e federal requests.

4.  In the **Name** field, enter the name of the agency.

5.  Select the **Ignore accents** check box to ignore accented characters in the XML file that you submit.

6.  In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: Select the **Cancel as Event** check box to use the event web service to cancel electronic fiscal documents.

7.  In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Authority type** field, select one of the following options to indicate the type of authority:
    
      - **Common** – The authority is a common authority.
    
      - **SCAN** – The authority is a Sistema de Contingência do Ambiente Nacional (SCAN) authority that is used for the SCAN contingency mode.
        

        > [!NOTE]
        > <P>You can set up only one authority for the SCAN contingency mode.</P>



8.  In the **Web services** grid, click **New**.

9.  In the **Environment** field, select an environment for the web service from the following options:
    
      - **Testing** – The NF-e process is performed in the Secretaria da Fazenda (SEFAZ) test environment.
    
      - **Production** – The NF-e process is performed in the SEFAZ production environment.

10. In the **Web service** field, select the type of XML message that is used to communicate with the authority by using the web service environment address:
    
      - **NF-e** – Send an NF-e and receive an NF-e protocol.
    
      - **Cancel** – Send an NF-e cancellation.
    
      - **Discard** – Send a discarded NF-e.
    
      - **NF-e inquiry** – Send an inquiry about the NF-e status.
    
      - **NF-e return** – Return an inquiry NF-e that contains the NF-e status.
    
      - **NF-e events** – Send a correction letter NF-e and cancel an NF-e as an event.
    
      - **Service inquiry** – Verify the NF-e web service status.
        

        > [!NOTE]
        > <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



11. In the **Version** field, enter the version number of the fiscal document layout.

12. In the **Internet address** field, enter the address for the web service.

## Set up an NF-e rejection code

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **NF-e federal parameters**.

2.  Click **Rejection codes**.

3.  Click **New** to create a rejection code for an NF-e.

4.  In the **NF-e rejection code** field, enter the NF-e rejection code.

5.  In the **Description** field, enter a description for the NF-e rejection code.

6.  In the **Message type** field, select the type of message:
    
      - **NF-e** – The NF-e message.
    
      - **Cancel** – The canceled NF-e message.
    
      - **Discard** – The discarded NF-e message.

7.  In the **Fiscal document status** field, select the fiscal document status that is mapped to the rejection code.

## Set up an NF-e schema

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **NF-e federal parameters**.

2.  Click **Schemas**.

3.  Click **New** to create a NF-e schema.

4.  In the **Schema type** field, select the type of NF-e schema:
    
      - **NF-e**
    
      - **Cancel**
    
      - **Discard**
    
      - **Correction letter**
    
      - **Cancel as Event**
        

        > [!NOTE]
        > <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



5.  In the **The version of the NF-e feature** field, select the version number of the NF-e feature.

6.  In the **Schema** field, enter the path and the file name of the XML schema that is used to validate an NF-e XML message that was rejected.

## See also

[(BRA) NF-e federal parameters (form)](https://technet.microsoft.com/library/jj933509\(v=ax.60\))

[(BRA) About NF-e schemas and processes](bra-about-nf-e-schemas-and-processes.md)

[(BRA) About the NF-e process](bra-about-the-nf-e-process.md)

  


