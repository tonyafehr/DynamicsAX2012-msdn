﻿---
title: ReleaseUpdateDB60_Payroll.updatePRLDeductionArrear Upgrade Script
TOCTitle: ReleaseUpdateDB60_Payroll.updatePRLDeductionArrear Upgrade Script
ms:assetid: 89f1cd91-3efe-7a8b-1dab-6bbb98a71765
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ736389(v=AX.60)
ms:contentKeyID: 49709579
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Payroll.updatePRLDeductionArrear Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Payroll</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updatePRLDeductionArrear</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates records in the PRLDeductionArrear table.</p></td>
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
<td><p>Payroll</p></td>
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
<td><p>PRLDeductionArrear</p></td>
</tr>
<tr class="even">
<td><p>PRLEmployeePayElementsTransPosted</p></td>
</tr>
<tr class="odd">
<td><p>PRLDeductionCodeTable</p></td>
</tr>
</tbody>
</table>


## Remarks

Updates the AccountingCurrencyAmount, PayStatement, and Benefit fields of the PRLDeductionArrear table based on the PRLEmployeePayElementsTransPosted and PRLDeductionCodeTable tables.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: PRLDeductionArrear</p></th>
<th><p>To Table: PRLDeductionArrear</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Amount</p></td>
<td><p>AccountingCurrencyAmount</p></td>
</tr>
</tbody>
</table>

  


