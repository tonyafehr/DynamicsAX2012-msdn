﻿---
title: ReleaseUpdateDB60_Trv.updateCostSplittedLines Upgrade Script
TOCTitle: ReleaseUpdateDB60_Trv.updateCostSplittedLines Upgrade Script
ms:assetid: e335744f-3af8-88f5-1a0c-ce1a053638f8
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ737344(v=AX.60)
ms:contentKeyID: 49711786
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Trv.updateCostSplittedLines Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Trv</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateCostSplittedLines</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Creates distributions for the cost split header line by using split lines, and delete cost split lines. This only applies to expense lines that are set to approved or created states.</p></td>
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
<td><p>Expense management</p></td>
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
<td><p>DEL_TrvExpTrans_Proj</p></td>
</tr>
<tr class="even">
<td><p>TrvExpTrans</p></td>
</tr>
<tr class="odd">
<td><p>ProjectAccountingDistribution</p></td>
</tr>
</tbody>
</table>

  


