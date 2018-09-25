---
title: Fix Element IDs (SQL patch script for AX 2012 R2 + CU6 upgrade scenarios)
TOCTitle: Fix Element IDs (SQL patch script for AX 2012 R2 + CU6 upgrade scenarios)
ms:assetid: 7206ce21-ece4-4ca1-9383-e2b07c0637e7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn313121(v=AX.60)
ms:contentKeyID: 54940413
ms.date: 10/15/2014
mtps_version: v=AX.60
---

# Fix Element IDs (SQL patch script for AX 2012 R2 + CU6 upgrade scenarios) 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

This topic provides a SQL script to repair incorrect element IDs when upgrading to Microsoft Dynamics AX 2012 R2 + CU6 from any of the following configurations:

  - Microsoft Dynamics AX 2012 + CU4

  - Microsoft Dynamics AX 2012 + CU5

  - Microsoft Dynamics AX 2012 Feature Pack + CU4

  - Microsoft Dynamics AX 2012 Feature Pack + CU5

To upgrade from any of these configurations to Microsoft Dynamics AX 2012 R2 + CU6, complete the following steps.

1.  Copy the extracted CU6 folder into the Updates folder of the Microsoft Dynamics AX 2012 R2 installation media. This will provide slipstreaming of CU6 during installation. For more information about slipstreaming, see [Include cumulative updates and hotfixes in a new installation (slipstreaming)](include-cumulative-updates-and-hotfixes-in-a-new-installation-slipstreaming.md)

2.  Run setup.exe and complete the Microsoft Dynamics AX 2012 R2 installation steps.

3.  Stop the AOS.

4.  Run the SQL script, provided below. First open SQL Server Management Studio, then use Object Explorer to navigate to the Microsoft Dynamics AX model store database, and then right-click the database name. Click **New query** and paste the SQL script in the query window that opens. Click **Execute** to run the script.

5.  Start the AOS.

6.  Run the command:
    
    AX32.exe –startupcmd=kernelcompileall

7.  Proceed with the upgrade process as described in [Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3](scenario-perform-in-place-upgrade-to-ax-2012-r2-or-ax-2012-r3.md), beginning at the section “Back up the test system model store.”

## Program listing of the SQL patch script


> [!NOTE]
> <P>The database names in the script are Microsoft Dynamics AX defaults. If you have changed the names to a non-default value, you will need to edit the script accordingly. Keep in mind that beginning with Microsoft Dynamics AX 2012 R2, the single database of previous Microsoft Dynamics AX 2012 versions is replaced with two databases, one containing business data and the other containing the model store.</P>



    DECLARE @oldModelDBName nvarchar(500)
    DECLARE @newModelDBName nvarchar(500)
    /*
    Usage:
    Replace the value for @newModelDBName with the name of your Microsoft Dynamics AX 2012 R2 model store database.
    Replace the value for @oldModelDBName with the name of your Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack database.
    */
    SET @newModelDBName = 'MicrosoftDynamicsAX_model'
    SET @oldModelDBName = 'MicrosoftDynamicsAX'
    
    
    DECLARE @usingStmt [NVARCHAR](MAX)
    DECLARE @dropModelPatchTableStmt [NVARCHAR](MAX)
    DECLARE @dropCollisionsTableStmt [NVARCHAR](MAX)
    DECLARE @selectIntoModelPatchTableStmt [NVARCHAR](MAX)
    DECLARE @updateAxIdsStmt [NVARCHAR](MAX)
    DECLARE @updateParentAxIdsStmt [NVARCHAR](MAX)
    DECLARE @selectIntoAxIDCollisionsTableStmt [NVARCHAR](MAX)
    DECLARE @axIdCollisionsStmt[NVARCHAR](MAX)
    
    SELECT @usingStmt = 'USE '+ @oldModelDBName
    EXEC(@usingStmt)
    
    SELECT @dropModelPatchTableStmt = 'IF EXISTS (
    SELECT * FROM ['+@oldModelDBName+'].[SYS].[TABLES] WHERE [NAME] = ''MODELSTOREAXIDPATCH''
    )
    DROP TABLE ['+@oldModelDBName+ ']..[MODELSTOREAXIDPATCH]'
    EXEC (@dropModelPatchTableStmt)
    
    SELECT @dropCollisionsTableStmt = 'IF EXISTS (
    SELECT * FROM ['+@oldModelDBName+'].[SYS].[TABLES] WHERE [NAME] = ''MODELSTOREAXIDCOLLISIONS''
    )
    DROP TABLE ['+@oldModelDBName+ ']..[MODELSTOREAXIDCOLLISIONS]'
    EXEC (@dropCollisionsTableStmt)
    
    BEGIN TRAN
    
    SELECT @selectIntoModelPatchTableStmt = 'SELECT * INTO ['+@oldModelDBName+']..[MODELSTOREAXIDPATCH] FROM (
    SELECT [OLDMODELELEMENT].[AXID] AS OLDAXID, [NEWMODELELEMENT].[AXID] AS NEWAXID, [NEWMODELELEMENT].[PARENTID] AS NEWPARENTID,
    [NEWMODELELEMENT].[PARENTHANDLE] AS NEWPARENTHANDLE, [NEWMODELELEMENT].[ELEMENTHANDLE] AS NEWELEMENTHANDLE,[NEWMODELELEMENT].[NAME] AS NEWELEMENTNAME, 
    [NEWMODELELEMENT].[ELEMENTTYPE] AS NEWMODELELEMENTTYPE
    FROM [' + @oldModelDBName + ']..[MODELELEMENT] OLDMODELELEMENT
    INNER JOIN [' + @newModelDBName + ']..[MODELELEMENT] NEWMODELELEMENT
    ON ([OLDMODELELEMENT].[ORIGIN] = [NEWMODELELEMENT].[ORIGIN])
    WHERE [OLDMODELELEMENT].[ORIGIN] != ''00000000-0000-0000-0000-000000000000''
    AND [OLDMODELELEMENT].[AXID] != [NEWMODELELEMENT].[AXID]) CHANGEDAXIDS'
    EXEC(@selectIntoModelPatchTableStmt)
    
    SELECT @selectIntoAxIDCollisionsTableStmt = 'SELECT * INTO ['+@oldModelDBName+']..[MODELSTOREAXIDCOLLISIONS] FROM (
    SELECT [NEWMODELELEMENT].[AXID] AS NEWAXID, [NEWMODELELEMENT].[PARENTID] AS NEWPARENTID, [NEWMODELELEMENT].[PARENTHANDLE] AS NEWPARENTHANDLE, 
    [NEWMODELELEMENT].[ELEMENTTYPE] AS NEWELEMENTTYPE, [NEWMODELELEMENT].[NAME] AS NEWELEMENTNAME, [NEWMODELELEMENT].[ELEMENTHANDLE] AS NEWELEMENTHANDLE, 
    [NEWMODELELEMENT].[PARTOFINHERITANCE] AS PARTOFINHERITANCE
    FROM ['+@newModelDBName+']..[MODELELEMENT] NEWMODELELEMENT 
    INNER JOIN ['+@oldModelDBName+']..[MODELSTOREAXIDPATCH] AXIDPATCH 
    ON ([NEWMODELELEMENT].[AXID] = [AXIDPATCH].[OLDAXID] 
    AND [NEWMODELELEMENT].[PARENTHANDLE] = [AXIDPATCH].[NEWPARENTHANDLE]
    AND [NEWMODELELEMENT].[ELEMENTTYPE] = [AXIDPATCH].[NEWMODELELEMENTTYPE]
    AND [AXIDPATCH].[NEWELEMENTHANDLE] != [NEWMODELELEMENT].[ELEMENTHANDLE])
    WHERE 
    NOT EXISTS (SELECT [NEWELEMENTHANDLE] FROM ['+@oldModelDBName+']..[MODELSTOREAXIDPATCH] PATCHLIST 
    WHERE PATCHLIST.[NEWELEMENTHANDLE] = [NEWMODELELEMENT].[ELEMENTHANDLE])) COLLISIONS'
    EXEC(@selectIntoAxIDCollisionsTableStmt)
    
    
    SELECT @AxIdCollisionsStmt =   'DECLARE collidingElementsCursor CURSOR FOR 
    SELECT [NEWELEMENTTYPE], [NEWPARENTID], [PARTOFINHERITANCE], [NEWELEMENTHANDLE] from ['+@oldModelDBName+']..[MODELSTOREAXIDCOLLISIONS]
    OPEN collidingElementsCursor
    
    DECLARE @newElementType INT
    DECLARE @newParentId INT
    DECLARE @partOfInheritance INT
    DECLARE @newElementHandle INT
    
    FETCH NEXT FROM collidingElementsCursor
    INTO @newElementType, @newParentId, @partOfInheritance, @newElementHandle
    
    WHILE @@FETCH_STATUS = 0
    BEGIN
    DECLARE @newAxID INT;
    
    EXEC ['+@newModelDBName+']..XU_GetNextAvailableAxId @newElementType, @newParentId, @partOfInheritance, @newAxID OUTPUT
    
    UPDATE ['+@newModelDBName+']..[MODELELEMENT] SET [AXID] = @newAxID 
    WHERE [MODELELEMENT].[ELEMENTHANDLE] = @newElementHandle
    
    UPDATE ['+@newModelDBName+']..[MODELELEMENT] SET [PARENTID] = @newAxID 
    WHERE [MODELELEMENT].[PARENTHANDLE] = @newElementHandle
    
    FETCH NEXT FROM collidingElementsCursor
    INTO @newElementType, @newParentId, @partofInheritance, @newElementHandle
    END
    
    CLOSE collidingElementsCursor
    DEALLOCATE collidingElementsCursor'
    EXEC(@AxIdCollisionsStmt)
    
    SELECT @updateAxIdsStmt = 'UPDATE [' + @newModelDBName + ']..[MODELELEMENT] SET [AXID] = ['+@oldModelDBName+']..[MODELSTOREAXIDPATCH].[OLDAXID]
    FROM ['+@oldModelDBName+']..[MODELSTOREAXIDPATCH ]
    WHERE [' + @newModelDBName + ']..[MODELELEMENT].[ELEMENTHANDLE] = ['+@oldModelDBName+']..[MODELSTOREAXIDPATCH].[NEWELEMENTHANDLE]
    AND [' + @newModelDBName + ']..[MODELELEMENT].[NAME] = ['+@oldModelDBName+']..[MODELSTOREAXIDPATCH].[NEWELEMENTNAME]
    AND [' + @newModelDBName + ']..[MODELELEMENT].[ELEMENTTYPE] = ['+@oldModelDBName+']..[MODELSTOREAXIDPATCH].[NEWMODELELEMENTTYPE]'
    EXEC(@updateAxIdsStmt)
    
    SELECT @updateParentAxIdsStmt = 'UPDATE [' + @newModelDBName + ']..[MODELELEMENT] SET [PARENTID] = ['+@oldModelDBName+']..[MODELSTOREAXIDPATCH].[OLDAXID]
    FROM ['+@oldModelDBName+']..[MODELSTOREAXIDPATCH]
    WHERE [' + @newModelDBName + ']..[MODELELEMENT].[PARENTHANDLE] = ['+@oldModelDBName+']..[MODELSTOREAXIDPATCH].[NEWELEMENTHANDLE]'
    EXEC(@updateParentAxIdsStmt)
    
    COMMIT TRAN

  


