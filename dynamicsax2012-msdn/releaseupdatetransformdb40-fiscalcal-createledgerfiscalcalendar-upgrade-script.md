﻿---
title: ReleaseUpdateTransformDB40_FiscalCal.createLedgerFiscalCalendar Upgrade Script
TOCTitle: ReleaseUpdateTransformDB40_FiscalCal.createLedgerFiscalCalendar Upgrade Script
ms:assetid: 80259603-2663-d403-eb75-f44e5904b067
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685894(v=AX.60)
ms:contentKeyID: 49709348
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateTransformDB40\_FiscalCal.createLedgerFiscalCalendar Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateTransformDB40_FiscalCal</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>createLedgerFiscalCalendar</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Creates the data in the FiscalCalendar table from the LedgerPeriod table and also updates the FiscalCalendar field in the Ledger table.</p></td>
</tr>
<tr class="even">
<td><p><strong>Script Type</strong></p></td>
<td><p>Preprocessing 60: Live</p></td>
</tr>
<tr class="odd">
<td><p><strong>Microsoft Dynamics AX Source</strong></p></td>
<td><p>Microsoft Dynamics AX 4.0</p></td>
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
<td><p>FiscalCalendar</p></td>
</tr>
</tbody>
</table>


## Remarks

The new calendar is created with the name of Financial, which contains all the years upgraded from the LedgerPeriod table.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: LedgerPeriod</p></th>
<th><p>To Table: FiscalCalendar</p></th>
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
<td><p>FiscalCalendar</p></td>
<td><p>CalendarId</p></td>
<td><p>FiscalCalendarId</p></td>
</tr>
<tr class="even">
<td><p>FiscalCalendar</p></td>
<td><p>Description</p></td>
<td><p>Description</p></td>
</tr>
<tr class="odd">
<td><p>Ledger</p></td>
<td><p>FiscalCalendar</p></td>
<td><p>RefRecId</p></td>
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
<td><p>LedgerPeriod</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  


