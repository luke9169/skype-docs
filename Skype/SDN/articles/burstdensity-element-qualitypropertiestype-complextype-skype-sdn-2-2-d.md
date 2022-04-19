---
title: BurstDensity element (QualityPropertiesType complexType) Schema D
TOCTitle: BurstDensity element
ms:assetid: 7e9ced1d-5232-3d1a-e36b-08af16380c27
ms:mtpsurl: https://msdn.microsoft.com/library/Mt149434(v=office.16)
ms:contentKeyID: 65855381
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# BurstDensity element (Schema D)

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Average burst density, as specified in \[RFC3611\] section 4.7.2, is computed with a Gmin=16 for the received RTP packets. This metric is reported for audio streams when available and measures the average density of packet Loss during bursts of losses during the call. This field MUST be populated and MUST be set to zero if no packets have been received.

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

    <xs:element name="BurstDensity"  type="xs:unsignedInt">
    
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

