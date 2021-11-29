---
title: Set up advanced bank reconciliation import
TOCTitle: Set up advanced bank reconciliation import
ms:assetid: 1950939d-c357-45c0-8b31-b02f6f4310bd
ms:mtpsurl: https://technet.microsoft.com/library/JJ729751(v=AX.60)
ms:contentKeyID: 49564917
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up advanced bank reconciliation import 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012 R2, you can import electronic banks statements and reconcile the imported bank statements with bank documents.

## Set up the import process


> [!NOTE]
> <P>The following steps should be performed by system administrators with knowledge of the AOT.</P>



1.  In the AOT, under the **Resources**, locate the bank files. These files will translate the electronic bank statement from their original format to a format that Microsoft Dynamics AX can use.
    

    > [!NOTE]
    > <P>Formats include ISO20022, BAI2 and MT940.</P>



2.  Right-click the file, and then click **Open**.

3.  In the **Preview** form, select **XML document** in the **File type** field.

4.  Click **Export** to generate XSLT templates.

5.  After all files have been exported and created, close the **Preview** form.

6.  Go to **Tools** \> **Application Integration Framework** \> **Manage transforms** to create file transforms for supported electronic bank statement formats.

7.  In the **Manage transforms** form, click **New** to create a new transform.

8.  Click **Load** to select the XSML templates that you created above.
    

    > [!NOTE]
    > <P>You must change the file type to <STRONG>XSLT files</STRONG> to locate the created templates.</P>



9.  Close the AOT.

10. In Microsoft Dynamics AX, Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

11. In the **Adapter** field, select **File system adapter**.

12. In the **URI** field, select a location to put the bank files.

13. On the **Service contract customizations** FastTab, click **Service operations**.

14. In the **Select service operations** form, select the following from **Remaining service operations** and move to **Selected service operations**:
    
      - **BankStmtService.create**
    
      - **BankStmtService.delete**
    
      - **BankStmtService.find**
    
      - **BankStmtService.getChangedKeys**
    
      - **BankStmtService.getKeys**
    
      - **BankStmtService.read**
    

    > [!NOTE]
    > <P>These services will be available only if a bank account has the <STRONG>Advanced bank reconciliation</STRONG> check box selected on the <STRONG>Bank accounts</STRONG> form.</P>



15. On the **Processing options** FastTab, select the check box next to **Transform all requests** and click **Inbound transforms**.

16. In the **Inbound transforms** form, click **New** to create a new inbound transform.

17. In the **Transform name** field, select the name of the transform that was created. Close the **Inbound transforms** form.

18. On the **Troubleshooting** FastTab, in the **Logging mode** field, select **Original document**.

19. On the **Security** FastTab, in the **Restrict to partition:** field, select **initial**.

20. In the **Restrict to company** field, select the company that you are working in.

21. Click **Activate** to activate the inbound port.
    
    For more information, see [AIF inbound ports (form)](https://technet.microsoft.com/library/hh208821\(v=ax.60\)).

  


