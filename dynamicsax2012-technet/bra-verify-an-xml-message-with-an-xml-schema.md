---
title: (BRA) Verify an XML message with an XML schema
TOCTitle: (BRA) Verify an XML message with an XML schema
ms:assetid: 5102bd8e-4e7b-42ee-8ec9-813efb0a1315
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ933516(v=AX.60)
ms:contentKeyID: 50935129
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- schema
- xml
- BRA
- Brazil
- xml message
---

# (BRA) Verify an XML message with an XML schema 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedure to verify a Nota Fiscal eletrônica (NF-e) XML message by using an XML schema.

1.  Click **General ledger** \> **Inquiries** \> **Fiscal documents** \> **All fiscal documents**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Fiscal documents** \> **All fiscal documents**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Fiscal documents** \> **All fiscal documents**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Fiscal documents** \> **All fiscal documents**.

2.  Select a fiscal document.

3.  On the **Action Pane**, on the **NF-e federal** tab, click **XML document**.

4.  In the **View XML message** form , on the **NF-e** tab, click **Validate XML** to validate the NF-e XML message by using the XML schema file that you specified in the **Schema** field in the **Schemas** area in the **NF-e federal parameters** form.
    

    > [!NOTE]
    > <P>If the NF-e is rejected because of errors in the schema, the errors are displayed.</P>



You can also validate an XML message by using an XML schema when you post an electronic fiscal document. In the **Fiscal establishments** form, select the **Validate XML schema on posting** check box.

## See also

[(BRA) All fiscal documents (list page)](https://technet.microsoft.com/en-us/library/jj710567\(v=ax.60\))

[(BRA) NF-e federal parameters (form)](https://technet.microsoft.com/en-us/library/jj933509\(v=ax.60\))

[(BRA) Fiscal establishments (form)](https://technet.microsoft.com/en-us/library/jj933531\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

