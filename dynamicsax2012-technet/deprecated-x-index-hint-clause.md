---
title: 'Deprecated: X++ index hint clause'
TOCTitle: X++ index hint clause
ms:assetid: 2424146a-0681-442c-a316-a55ccd4f8d35
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn507158(v=AX.60)
ms:contentKeyID: 59623247
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: X++ index hint clause 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, the administrative tool named **Microsoft Dynamics AX Server Configuration Utility** offered an option that was labeled **Allow INDEX hints on queries**. Access to this configuration option is no longer available in the configuration utility for Microsoft Dynamics AX 2012, and the option is deprecated. In the system the option’s value is **False** by default.

Any legacy X++ select statements that include the index hint clause still run fine in Microsoft Dynamics AX 2012. But due to the default value of **False**, the index hint clause is now *ignored*, such as in the following code example:

```X++
    static void Main(Args _args)    // X++
    {
        CustTable custTableBuffer;
    
        custTableBuffer.disableCache(true);
    
        select
            generateOnly
            forceLiterals
                MainContactWorker
            from
                custTableBuffer
            INDEX HINT HcmWorkerIdx   //index hint is IGNORED in AX 2012.
            where
                custTableBuffer.MainContactWorker == 0
        ;
    
        Global::info(CustTableBuffer.getSQLStatement());
    }

    
    /*****
    The following is output pasted from the Infolog window, with
    whitespace added.
    Notice that this resultant SELECT statement, built by the AX AOS for
    Microsoft SQL Server, lacks an INDEX clause.
    That absence indicates that the AX X++ compiler ignored
    the 'index hint' clause.
    
    
    SELECT
        T1.MAINCONTACTWORKER, T1.RECID
      FROM
        CUSTTABLE T1
      WHERE
        ( ( (PARTITION=5637144576) AND
            (DATAAREAID=N'dat')
          ) AND
          (MAINCONTACTWORKER=0)
        )
    *****/
```    

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Reason for deprecation</p></td>
<td><p>This feature was rarely used. This feature began to create complications in the evolving development environment, so the feature was removed.</p></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>No. There is no supported replacement for this feature.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>This feature was not particular to any application module.</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>Any legacy custom X++ code that uses the index hint clause still compiles and runs in Microsoft Dynamics AX 2012.</p></td>
</tr>
</tbody>
</table>

  


