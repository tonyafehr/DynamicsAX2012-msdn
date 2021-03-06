﻿---
title: ReleaseUpdateTransformDB50_LedgerTrx.taxTransPreProcessingDelta Upgrade Script
TOCTitle: ReleaseUpdateTransformDB50_LedgerTrx.taxTransPreProcessingDelta Upgrade Script
ms:assetid: 51fa2ba2-a430-2c78-8df5-31f953d57c05
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685570(v=AX.60)
ms:contentKeyID: 49708264
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateTransformDB50\_LedgerTrx.taxTransPreProcessingDelta Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateTransformDB50_LedgerTrx</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>taxTransPreProcessingDelta</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Handles the delta pre-processing of records in the TaxTrans table.</p></td>
</tr>
<tr class="even">
<td><p><strong>Script Type</strong></p></td>
<td><p>Preprocessing 60: Delta</p></td>
</tr>
<tr class="odd">
<td><p><strong>Microsoft Dynamics AX Source</strong></p></td>
<td><p>Microsoft Dynamics AX 4.0</p>
<p>Microsoft Dynamics AX 2009</p></td>
</tr>
</tbody>
</table>


## Affected Modules and Tables

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Modules</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>General ledger</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Tables</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>TaxTrans</p></td>
</tr>
</tbody>
</table>


## Remarks

Each TaxTrans record will be normalized into a new TaxTransGeneralJournalAccountEntry linking table. This is done for each record that has a value for the AccountNum, OperationAccount, and TaxOffsetAccountUseTax fields.

This is a sergeant method that calls the other associated methods to perform the normalization against each record that has been created, updated, or deleted in the TaxTrans table since the live pre-processing step of the upgrade was run.

  


