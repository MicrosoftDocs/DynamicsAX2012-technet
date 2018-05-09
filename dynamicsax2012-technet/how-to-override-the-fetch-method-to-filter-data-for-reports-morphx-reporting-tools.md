---
title: 'How to: Override the fetch Method to Filter Data for Reports (MorphX Reporting Tools)'
TOCTitle: 'How to: Override the fetch Method to Filter Data for Reports'
ms:assetid: cc342c22-4a3c-423c-bd55-c18263e122c9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Bb395110(v=AX.60)
ms:contentKeyID: 35290365
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Override the fetch Method to Filter Data for Reports (MorphX Reporting Tools) 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can override the fetch method to filter the data that is displayed in a report. This override does not reduce the number of records that are returned by the query of the report. Instead it prevents some records from being sent to the final report. Each record is examined by the branching logic you add to the fetch method. Branching determines which records to give to the send method. Those records appear in the final report.


> [!NOTE]
> <P>Do not call super() when you override the fetch method in a report.</P>



By default, each record that is returned by the query appears in the report. To reduce the number of records returned, add range restrictions to the query. Report ranges are more efficient than overriding the fetch method; however, report ranges are less expressive. For information about adding ranges to queries, see [Query Elements in the AOT](https://technet.microsoft.com/en-us/library/bb278121\(v=ax.60\)).

## Example

The following code example loops through each record that is returned by the query. The code tests a field in each record and branches to a send method call for records that belong in the report.

In this example, the BankAccountTable table is the only data source for the report. The fetch method in the report is overridden with the following code.

    public boolean fetch()
    {
        boolean retCode = false;
        BankAccountTable bankAccountTableRec;
        QueryRun qrun;
        ;
        // Use the queryRun object that is associated with the
        // report; element refers to the report.
        qrun = new QueryRun(element);
    
        // Verify that the report dialog works.
        if (! qrun.prompt())
        {
            return retCode;
        }
    
        // Loop through each record from the data source query of the report.
        while (qrun.next())
        {
            // Get the BankAccountTable fields from the query record.
            bankAccountTableRec = qrun.get(TableNum(BankAccountTable));
    
            // Exclude ODDBANK from the visible report.
            if (bankAccountTableRec.AccountID != "ODDBANK")
                {
                    // Include the current record in the report.
                    element.send(bankAccountTableRec);
                }
        }
        retCode = true;
    
        // retCode = super(); // Do not call super() when you override the fetch method.
        return retCode;
    }

## See also

[Report Methods (MorphX Reporting Tools)](report-methods-morphx-reporting-tools.md)

