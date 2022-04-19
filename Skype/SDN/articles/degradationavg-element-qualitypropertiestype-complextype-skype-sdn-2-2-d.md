---
title: DegradationAvg element (QualityPropertiesType complexType) (Schema D)
TOCTitle: DegradationAvg element
ms:assetid: 8482ec9b-f974-4e46-f401-d24709f3f2d5
ms:mtpsurl: https://msdn.microsoft.com/library/Mt149465(v=office.16)
ms:contentKeyID: 65855412
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# DegradationAvg element (QualityPropertiesType complexType) (Schema D)

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Difference between the OverallAvg value and the maximum possible MOS-LQO for the audio codec used in the session. This metric is reported for audio streams when available.

## Element information

<table>
<colgroup>
<col />
<col />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p><a href="nonnegativedouble-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">NonNegativeDouble</a></p></td>
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

    <xs:element name="DegradationAvg"  type="NonNegativeDouble">
    
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

