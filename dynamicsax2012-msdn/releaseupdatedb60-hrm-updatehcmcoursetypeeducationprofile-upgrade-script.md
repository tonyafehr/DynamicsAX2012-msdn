﻿---
title: ReleaseUpdateDB60_HRM.updateHcmCourseTypeEducationProfile Upgrade Script
TOCTitle: ReleaseUpdateDB60_HRM.updateHcmCourseTypeEducationProfile Upgrade Script
ms:assetid: 391ac808-8558-e1cc-c7e8-2a545a0829eb
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685226(v=AX.60)
ms:contentKeyID: 49707678
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_HRM.updateHcmCourseTypeEducationProfile Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

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
<td><p>updateHcmCourseTypeEducationProfile</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Inserts records into the HcmCourseTypeEducationProfile table from the HRMCourseTypeEducationProfile table.</p></td>
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
<td><p>HcmCourseType</p></td>
</tr>
<tr class="even">
<td><p>HcmCourseTypeEducationProfile</p></td>
</tr>
<tr class="odd">
<td><p>HRMCourseTypeEducationProfile</p></td>
</tr>
<tr class="even">
<td><p>HRMEducationType</p></td>
</tr>
</tbody>
</table>


## Remarks

This upgrade will retain the data of each company. The CourseType field in the HcmCourseTypeEducationProfile table is the foreign key to the HcmCourseType table. The EducationDiscipline field in the HcmCourseTypeEducationProfile table is the foreign key to the HcmEducationDiscipline table.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: HRMCourseTypeEducationProfile</p></th>
<th><p>To Table: HcmCourseTypeEducationProfile</p></th>
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
<td><p>HcmCourseTypeEducationProfile</p></td>
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
<td><p>HRMCourseTypeEducationProfile</p></td>
<td><p>*</p></td>
</tr>
</tbody>
</table>

  


