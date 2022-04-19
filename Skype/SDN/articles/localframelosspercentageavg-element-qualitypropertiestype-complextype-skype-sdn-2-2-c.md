---
title: LocalFrameLossPercentageAvg element (QualityPropertiesType complexType) (Schema C)
TOCTitle: LocalFrameLossPercentageAvg element
ms:assetid: 1af349ff-e324-8424-1460-7a08ab9b2418
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404784(v=office.16)
ms:contentKeyID: 68250694
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# LocalFrameLossPercentageAvg element (Schema C)

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

(Deprecated, use VideoLocalFrameLossPercentageAvg instead) Average percentage of video frames lost as they are displayed to the user, including frames recovered from network losses. This metric is reported for video streams when available. (percent)

**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>

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

    <xs:element name="LocalFrameLossPercentageAvg"  type="xs:string">
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

<table>

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

