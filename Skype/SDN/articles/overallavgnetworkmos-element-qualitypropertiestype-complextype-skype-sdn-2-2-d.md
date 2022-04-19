---
title: OverallAvgNetworkMOS element (QualityPropertiesType complexType) (Schema D)
TOCTitle: OverallAvgNetworkMOS element
ms:assetid: 45ba3a59-5205-afc9-f4ea-69fded1c1c30
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170928(v=office.16)
ms:contentKeyID: 65855504
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# OverallAvgNetworkMOS element (Schema D)

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Average of MOS-LQO wideband, as specified by \[ITUP.800.1\] section 2.1.2, based on the audio codec used, the observed packet loss and inter-arrival packet jitter. This metric is reported for audio streams when available.


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

    <xs:element name="OverallAvgNetworkMOS"  type="NonNegativeDouble">
    
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

