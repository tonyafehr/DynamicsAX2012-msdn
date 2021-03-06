﻿---
title: ReleaseUpdateDB60_HRM.updateHcmEducationDisciplineGroup
TOCTitle: ReleaseUpdateDB60_HRM.updateHcmEducationDisciplineGroup
ms:assetid: 992b5cb5-469c-9a14-c79a-8430b4937a08
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ686263(v=AX.60)
ms:contentKeyID: 49709967
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_HRM.updateHcmEducationDisciplineGroup 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_HRM</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateHcmEducationDisciplineGroup</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Inserts records into the &lt;c&gt;HcmEducationDisciplineGroup&lt;/c&gt; table from the &lt;c&gt;HRMEducationGroupType&lt;/c&gt; table.</p></td>
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
<td><p>Human Resources</p></td>
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
<td><p>HcmEducationDisciplineGroup</p></td>
</tr>
<tr class="even">
<td><p>HRMEducationGroup</p></td>
</tr>
<tr class="odd">
<td><p>HRMEducationGroupType</p></td>
</tr>
<tr class="even">
<td><p>HRMEducationType</p></td>
</tr>
</tbody>
</table>


## Remarks

This upgrade will discard duplicates associated with discard duplicates upgrades with the \<c\>HcmEducationDisciplineGroup\</c\> table and the \<c\>HcmEducationDisciplineCategory\</c\> table. The \<c\>EducationDiscipline\</c\> field in the \<c\>HcmEducationDisciplineGroup\</c\> table is the foreign key to the \<c\>HcmEducationDiscipline\</c\> table. The \<c\>EducationDisciplineCategory\</c\> field in the \<c\>HcmEducationDisciplineGroup\</c\> table is the foreign key to the \<c\>HcmEducationDisciplineCategory\</c\> table.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: HRMEducationGroupType</p></th>
<th><p>To Table: HcmEducationDisciplineGroup</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
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
<td><p>HcmEducationDisciplineGroup</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Deleted Tables or Fields

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>HRMEducationGroupType</p></td>
<td><p>*</p></td>
</tr>
</tbody>
</table>

  


