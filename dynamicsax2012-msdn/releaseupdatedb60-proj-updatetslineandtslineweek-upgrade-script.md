﻿---
title: ReleaseUpdateDB60_Proj.updateTSLineAndTSLineWeek Upgrade Script
TOCTitle: ReleaseUpdateDB60_Proj.updateTSLineAndTSLineWeek Upgrade Script
ms:assetid: 1a035702-d462-366f-fd79-dce1ec3112ad
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ718640(v=AX.60)
ms:contentKeyID: 49706922
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Proj.updateTSLineAndTSLineWeek Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Proj</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateTSLineAndTSLineWeek</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates TSTimesheetLine and TSTimesheetLineWeek tables by using the new SFK fields and additional details that are based on the refactoring done in Microsoft Dynamics AX 2012.</p></td>
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
<td><p>Project</p></td>
</tr>
<tr class="even">
<td><p>Project</p></td>
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
<td><p>TSTimesheetLine</p></td>
</tr>
<tr class="even">
<td><p>TSTimesheetLineWeek</p></td>
</tr>
</tbody>
</table>


## New Tables or Fields

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
<th><p>Extended Data Type</p>
<p>-or- Base Enum</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>TSTimesheetLine</p></td>
<td><p>ProjPeriodTimesheetWeek</p></td>
<td><p>RefRecId</p></td>
</tr>
<tr class="even">
<td><p>TSTimesheetLineWeek</p></td>
<td><p>TSTimesheetLine</p></td>
<td><p>RefRecId</p></td>
</tr>
</tbody>
</table>

  


