---
title: (RUS) Create lines in the Financial reports generator
TOCTitle: (RUS) Create lines in the Financial reports generator
ms:assetid: 062c7e61-0114-4339-a4eb-e016fd487471
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ911229(v=AX.60)
ms:contentKeyID: 52075344
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- lines
- create lines
- financial reports generator
---

# (RUS) Create lines in the Financial reports generator 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Document templates** form to create lines in the financial reports generator (FRG) based on the template settings.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Select a template, and then click **Functions** \> **Create financial report lines**.

3.  In the **Update type** field, select how the lines are created, from the following options:
    
      - **Track new transactions** – Lines are inserted in an existing FRG report or lines are added to an empty FRG report. If the same lines already exist, new lines are not inserted. The cell codes that are specified in the **Cell** field on the **Field setup** form for the FRG report are used to identify the lines that already exist.
    
      - **Update** – The cells from an existing FRG report are updated.

4.  Click **OK**.

## See also

[(RUS) Document templates (form)](https://technet.microsoft.com/en-us/library/jj923585\(v=ax.60\))

[(RUS) Create or update FRG lines (form)](https://technet.microsoft.com/en-us/library/jj911375\(v=ax.60\))

[(EEUR) Report (form)](https://technet.microsoft.com/en-us/library/jj911237\(v=ax.60\))

[(EEUR) Field setup (form)](https://technet.microsoft.com/en-us/library/jj910976\(v=ax.60\))

[(RUS) Set up templates for electronic reporting](rus-set-up-templates-for-electronic-reporting.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

