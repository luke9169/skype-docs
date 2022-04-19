---
title: BitRateAvg element (QualityPropertiesType complexType) Schema C
TOCTitle: BitRateAvg element
ms:assetid: 65935f6b-1f0f-e4e9-0d68-031d002582df
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404704(v=office.16)
ms:contentKeyID: 68250616
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# BitRateAvg element (Schema C)

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Average bit rate, in bits per second, sent or received for a video stream and computed over the duration of the session. This includes raw video and transport bits. This metric is reported for video streams when available. (bits/s)

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

    <xs:element name="BitRateAvg"  type="xs:string">
    
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

