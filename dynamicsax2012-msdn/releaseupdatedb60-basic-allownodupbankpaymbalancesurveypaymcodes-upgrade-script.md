﻿---
title: ReleaseUpdateDB60_Basic.allowNoDupBankPaymBalanceSurveyPaymCodes Upgrade Script
TOCTitle: ReleaseUpdateDB60_Basic.allowNoDupBankPaymBalanceSurveyPaymCodes Upgrade Script
ms:assetid: 3295c059-82e8-b8e3-75ad-fa52379a4db4
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685074(v=AX.60)
ms:contentKeyID: 49707527
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Basic.allowNoDupBankPaymBalanceSurveyPaymCodes Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Basic</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowNoDupBankPaymBalanceSurveyPaymCodes</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the SurveyCodeIdx index in the BankPaymBalanceSurveyPaymCodes table not to allow duplicate records.</p></td>
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
<td><p>Basic</p></td>
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
<td><p>BankPaymBalanceSurveyPaymCodes</p></td>
</tr>
</tbody>
</table>


## Remarks

After updating the BankPaymBalanceSurvey surrogate key field with the value of the record ID field of the BankPaymBalanceSurvey table, the SurveyCodeIdx index is reset not to allow duplicate records. Truncated method name from the allowNoDupBankPaymBalanceSurveyPaymCodesSurveyCodeIdx method.

  


