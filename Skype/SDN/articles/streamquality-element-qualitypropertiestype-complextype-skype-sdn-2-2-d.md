---
title: StreamQuality element (QualityPropertiesType complexType) (Schema D)
TOCTitle: StreamQuality element
ms:assetid: dc0ff96d-4d78-caed-44a0-3849b2ffa941
ms:mtpsurl: https://msdn.microsoft.com/library/Mt171001(v=office.16)
ms:contentKeyID: 65855573
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# StreamQuality element (Schema D)

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Estimated quality of the stream: Good, Poor, Bad


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
<td><p><a href="streamqualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">StreamQualityType</a></p></td>
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

    <xs:element name="StreamQuality"  type="StreamQualityType">
    
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

<table>
<colgroup>
<col />
<col />
<col />
<col />
<col />
</colgroup>
<thead>
<tr class="header">
<th><p>Attribute</p></th>
<th><p>Type</p></th>
<th><p>Required</p></th>
<th><p>Description</p></th>
<th><p>Possible values</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Source</p></td>
<td><p>xs:string</p></td>
<td><p>optional</p></td>
<td><p>Source that cause the stream's quality determination.</p></td>
<td><p>Values of the xs:string type.</p></td>
</tr>
</tbody>
</table>

