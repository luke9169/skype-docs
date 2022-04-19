---
title: RecvSignalLevel element (QualityPropertiesType complexType) Schema D
TOCTitle: RecvSignalLevel element
ms:assetid: faec1495-0a59-9bd3-2ecf-f24e2963d293
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170962(v=office.16)
ms:contentKeyID: 65855540
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# RecvSignalLevel element Schema D

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Received signal level in units of dB. This metric is reported for audio streams when available. Average energy level of received audio is classified as mono speech, or left channel of stereo speech. (dB)


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
<td><p>xs:int</p></td>
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

    <xs:element name="RecvSignalLevel"  type="xs:int">
    
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

