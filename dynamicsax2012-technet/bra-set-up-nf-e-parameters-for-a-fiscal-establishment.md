---
title: (BRA) Set up NF-e parameters for a fiscal establishment
TOCTitle: (BRA) Set up NF-e parameters for a fiscal establishment
ms:assetid: 4ab2c619-bb27-481c-bb20-68f0ba4c9000
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ933513(v=AX.60)
ms:contentKeyID: 50935132
ms.date: 05/27/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- fiscal establishment
- electronic fiscal document parameters
- NF-e parameters
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up NF-e parameters for a fiscal establishment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedure to set up the parameters for a Nota Fiscal eletrônica (NF-e) for a fiscal establishment.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R3.</P>



1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Fiscal establishments**.

2.  Select or create a fiscal establishment. For more information, see [(BRA) Create a fiscal establishment](bra-create-a-fiscal-establishment.md).

3.  On the **NF-e federal** FastTab, in the **Certificate** field, select the name of the digital certificate that is used to assign XML messages to an NF-e.

4.  In the **Web service** field group, specify values in the following fields:
    
    1.  In the **Environment** field, select one of the following options to indicate the web service environment for the fiscal establishment:
        
          - **Testing** – The NF-e process is performed in the Secretaria da Fazenda (SEFAZ) test environment.
        
          - **Production** – The NF-e process is performed in the SEFAZ production environment.
    
    2.  In the **The version of the NF-e feature** field, select the version of the NF-e feature.
    
    3.  In the **Authority** field, select the identification code of the agency that receives, approves, or rejects NF-e federal requests for the fiscal establishment.

5.  In the **Approved NF-e**, **Canceled NF-e**, and **Correction letter** fields, select the identification codes that identify the email messages for approved NF-e, canceled NF-e, and collection letters.

6.  Select the **Preprinted security form** check box to use the preprinted forms for the security form contingency mode.

7.  Select the **Attach the DANFE as PDF file to email** check box to attach the DANFE PDF files to emails that are generated for issued electronic fiscal documents.

8.  Select the **Print DANFE when NF-e is approved** check box to print the Documento Auxiliar da Nota Fiscal Eletrônica (DANFE) automatically when the NF-e is approved.

9.  Select the **Validate XML schema on posting** check box to validate the XML schema when you post an electronic fiscal document.

10. Select the **Post only NF-e that have valid access keys** check box to post only the electronic fiscal documents that have access keys that are validated by the SEFAZ.

11. Select the **Block NF-e posting if XML does not match** check box to post only the electronic fiscal documents for which the XML document information matches the vendor invoice information.
    

    > [!NOTE]
    > <P>This control is available only if Microsoft Dynamics AX 2012 R3 is installed.</P>



## See also

[(BRA) About fiscal establishments](bra-about-fiscal-establishments.md)

[(BRA) Fiscal establishments (form)](https://technet.microsoft.com/en-us/library/jj933531\(v=ax.60\))

[(BRA) NF-e federal parameters (form)](https://technet.microsoft.com/en-us/library/jj933509\(v=ax.60\))

  


