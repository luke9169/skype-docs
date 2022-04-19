---
title: BurstDuration element (QualityPropertiesType complexType) Schema D
TOCTitle: BurstDuration element
ms:assetid: d486a2e7-9431-9d6c-7018-53a7779ada11
ms:mtpsurl: https://msdn.microsoft.com/library/Mt149435(v=office.16)
ms:contentKeyID: 65855386
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# BurstDuration element (Schema D)

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

The average burst duration, as specified in \[RFC3611\] section 4.7.2, is computed with a Gmin=16 for the received RTP packets. This metric is reported for audio streams when available. (ms) 

## Element information

<table>
<colgroup>
<col />
<col />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p>xs:unsignedInt</p></td>
</tr>
<tr class="even">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.D.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml

    <xs:element name="BurstDuration"  type="xs:unsignedInt">
    
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
<td><p><a href="properties-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Properties</a></p></td>
<td><p><a href="qualitypropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityPropertiesType</a></p></td>
<td><p>Properties of the media stream, including a selected set of quality metrics reported and thresholds that are used to determine a bad call.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

