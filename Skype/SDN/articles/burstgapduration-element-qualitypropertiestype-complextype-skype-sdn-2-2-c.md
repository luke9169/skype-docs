---
title: BurstGapDuration element (QualityPropertiesType complexType) (Schema C)
TOCTitle: BurstGapDuration element
ms:assetid: a9a78900-88ce-d1b8-49ee-92c19270be0e
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404712(v=office.16)
ms:contentKeyID: 68250625
description: The Average burst gap duration (in microsecond, ms), as specified in RFC3611 section 4.7.2, computed with a Gmin=16 for the received RTP packets.
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# BurstGapDuration element (Schema C)

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Average burst gap duration (in microsecond, ms), as specified in \[RFC3611\] section 4.7.2, computed with a Gmin=16 for the received RTP packets. This metric is reported for audio streams when available. 

## Element information

<table>
<colgroup>
<col />
<col />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p>xs:string</p></td>
</tr>
<tr class="even">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.C.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml

    <xs:element name="BurstGapDuration"  type="xs:string">
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

<table>
<colgroup>
<col />
<col />
<col />
</colgroup>
<thead>
<tr class="header">
<th><p>Element</p></th>
<th><p>Type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="properties-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Properties</a></p></td>
<td><p><a href="qualitypropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">QualityPropertiesType</a></p></td>
<td><p>Properties of the media stream, including a selected set of quality metrics reported and thresholds that are used to determine a bad call.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

