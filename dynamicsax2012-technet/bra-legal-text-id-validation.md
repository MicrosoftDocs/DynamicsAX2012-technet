---
title: (BRA) Legal text ID validation
TOCTitle: (BRA) Legal text ID validation
ms:assetid: ea46f1fc-61df-4e29-921c-6fd7c3f78488
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ714203(v=AX.60)
ms:contentKeyID: 49651312
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (BRA) Legal text ID validation [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In releases before Microsoft Dynamics AX 2012 R2, legal texts are created from the Accounts receivable and Accounts payable modules in the **Sales texts** and **Receipt invoice texts** forms, and are stored in two separate tables. You could create legal texts with same identification code in the **Sales texts** and **Receipt invoice texts** forms. For example, you could create a sales legal text and a purchase legal text with the same 001 identification code in the **Sales texts** and **Receipt invoice texts** forms.

In Microsoft Dynamics AX 2012 R2 and R3, the fiscal document texts are created in the **Fiscal document source texts** form and stored in one table. You cannot create duplicate fiscal document texts with the same identification code.

During upgrade, if sales and purchase legal texts with the same identification code are available in the source system, you must specify new unique identification codes and names for the fiscal document texts in Microsoft Dynamics AX 2012 R2 or R3. You can also specify the default fiscal document texts for direct import and withholding tax. This information is updated in the **Fiscal document** area in the **Brazilian parameters** form in Microsoft Dynamics AX 2012 R2 or R3.

In Microsoft Dynamics AX 2012 R2 and R3, the document handling framework is used to manage fiscal document texts, which are stored in the DocuRef table. During upgrade, you can also specify the identification code for the document type register that is created for all legal texts in the DocuRef table.

Use the following procedure to upgrade legal texts to Microsoft Dynamics AX 2012 R2 or R3.

1.  In the **Preprocessing upgrade checklist**, expand **Prepare application data for preprocessing**, and then click the **Legal text ID validation** task to open the **Legal text ID validation** form.

2.  Select a legal text.

3.  In the **NewTextID** field, update the identification code of the fiscal document text in Microsoft Dynamics AX 2012 R2.

4.  In the **Direct import** field group, in the **Text ID** and **Name** fields, enter an identification code and a name of the default fiscal document text for direct import in Microsoft Dynamics AX 2012 R2. The identification code is updated in the **Text ID** field in the **Import declaration** field group in the **Fiscal document** area in the **Brazilian parameters** form.

5.  In the **Withholding tax** field group, in the **Text ID** and **Name** fields, enter an identification code and a name of the default fiscal document text for withholding tax in Microsoft Dynamics AX 2012 R2. The identification code is updated in the **Text ID** field in the **Withholding tax text for issue fiscal document** field group in the **Fiscal document** area in the **Brazilian parameters** form.

6.  In the **Document type ID** field, enter an identification code for the document type register that is created for all the legal texts in the DocuRef table in Microsoft Dynamics AX 2012 R2.

7.  After you update the information for all legal texts, click **Set to ready for upgrade** to close the form and mark the upgrade task as complete.

## See also

[(BRA) Legal text ID validation (form)](https://technet.microsoft.com/en-us/library/jj713622\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

