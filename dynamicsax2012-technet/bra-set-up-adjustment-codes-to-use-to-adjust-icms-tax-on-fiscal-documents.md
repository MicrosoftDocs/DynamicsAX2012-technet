---
title: (BRA) Set up adjustment codes to use to adjust ICMS tax on fiscal documents
TOCTitle: (BRA) Set up adjustment codes to use to adjust ICMS tax on fiscal documents
ms:assetid: ef2b4e7c-d37d-4940-bde9-1efd0e67850f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn305887(v=AX.60)
ms:contentKeyID: 54912991
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- ICMS
- Forms.FBFiscalDocumentAdjustmentCodeICMS_BR
- MsDynAx060.Forms.FBFiscalDocumentAdjustmentCodeICMS_BR
---

# (BRA) Set up adjustment codes to use to adjust ICMS tax on fiscal documents 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In a Sistema Publico de Escrituração Digital (SPED) fiscal text file, record C197 includes information about adjustments of Imposto sobre Circulação de Mercadorias e Serviços (ICMS) information on fiscal documents. These adjustments on fiscal documents can be because of deferral, suspension, differential of aliquot, anticipation, and other situations of exception in ICMS tax. Before you can adjust ICMS tax amounts on fiscal documents, you must specify the adjustment to apply to the adjustments. This topic explains how to set up adjustment codes by using the **Adjustment and information for fiscal documents** form.


> [!NOTE]
> <P>The procedure for completing this task has changed for Microsoft Dynamics AX 2012 R3. For information that is specific to Microsoft Dynamics AX 2012 R3, see the section later in this topic.</P>



Not all Brazilian states allow for ICMS and ICMS-ST amounts to be adjusted. To determine whether adjustments are allowed in a specific state, see the SPED tables on the government website. [http://www.sped.fazenda.gov.br/spedtabelas/AppConsulta/publico/aspx/ConsultaTabelasExternas.aspx?CodSistema=SpedFiscal](http://www.sped.fazenda.gov.br/spedtabelas/appconsulta/publico/aspx/consultatabelasexternas.aspx?codsistema=spedfiscal)

## Set up adjustment codes for ICMS taxes on fiscal documents

1.  Click **Fiscal books** \> **Setup** \> **Tax adjustment codes** \> **Adjustment and information for fiscal documents**.

2.  In the **Adjustment and information for fiscal documents** form, enter an adjustment code in the **Identification** field and a description of the adjustment code.

3.  Select a state.

4.  Select a classification from the following options:
    
      - **0 – Credit**
    
      - **1 – Other credits**
    
      - **2 – Debit reversal**
    
      - **3 – Debits**
    
      - **4 – Other debits**
    
      - **5 – Credit reversal**
    
      - **6 - Deduction**
    
      - **7 – Special debits**
    
      - **9 – Information**

5.  Select an assessment type from the following options:
    
      - **Own operation**
    
      - **Operation ST**
    
      - **Other assessments**
    
      - **Assessment 1 block 1900**
    
      - **Assessment 2 block 1900**
    
      - **Assessment 3 block 1900**
    
      - **Informative**

6.  Select a responsibility from the following options:
    
      - **Own**
    
      - **Optional**
    
      - **Informative**

7.  Select a tax payment type from the following options:
    
      - **0: Collection**
    
      - **1: Spontaneous collecting**
    
      - **2: Collection by infraction**
    
      - **3: Fiscal incentive**
    
      - **9: Informative**

8.  Select source of the tax from the following options:
    
      - **0: Goods**
    
      - **1: Transportation**
    
      - **2: Communication**
    
      - **3: Electric power**
    
      - **9: Informative**
    
    The **Adjustment code** field is filled in automatically, based on the entries in other fields in this form.

9.  Enter the occurrence code for the GIA fiscal obligation.

10. In the **Valid from** and **Valid to** fields, enter the first and last dates that the adjustment codes are applicable.

11. On the **Payment** FastTab, select the **Other debit** check box if you want to create an additional tax adjustment payment that is not included in the periodic payment.

12. On the **Posting** FastTab, in the **Company accounts** field, select the legal entity where the tax adjustment transactions will be posted.

13. In the **Sales tax code** field, select the tax code that will be used to select the accounts receivable or accounts payable account. The account that is selected depends on whether the tax adjustment is a debit or credit. For more information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md).

14. Select the main account that will be used to post the revenue or expense part of the adjustment transaction.

15. To create another adjustment code, click **New**, and then repeat steps 2 through 14.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

