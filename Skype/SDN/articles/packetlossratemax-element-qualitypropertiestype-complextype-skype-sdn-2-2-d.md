---
title: PacketLossRateMax element (QualityPropertiesType complexType) (Schema D)
TOCTitle: PacketLossRateMax element
ms:assetid: 02627ac9-06c8-be10-c5a6-f2089f963c76
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170935(v=office.16)
ms:contentKeyID: 65855511
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# PacketLossRateMax element (Schema D)

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Maximum fraction lost, as specified in \[RFC3550\] section 6.4.1, computed over the duration of the session. This metric is reported for all available modalities/media types. (percent)


**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<colgroup>
<col />
<col />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p><a href="doublebetween0and100-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">DoubleBetween0And100</a></p></td>
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

    <xs:element name="PacketLossRateMax"  type="DoubleBetween0And100">
    
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

