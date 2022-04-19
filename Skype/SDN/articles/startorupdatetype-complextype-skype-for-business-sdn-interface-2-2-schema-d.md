---
title: StartOrUpdateType complexType (Schema D)
TOCTitle: StartOrUpdateType complexType
ms:assetid: 7023ae43-40d9-c4b8-d8eb-530cb383130e
ms:mtpsurl: https://msdn.microsoft.com/library/Mt171075(v=office.16)
ms:contentKeyID: 65855648
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# StartOrUpdateType complexType (Schema D)

(Skype for Business SDN Interface 2.2, Schema "D")


**In this article**  
Type information  
Definition  
Elements and attributes  

## Type information

<table>
<colgroup>
<col />
<col />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.D.XSD</p></td>
</tr>
<tr class="odd">
<td><p><strong>Extension base</strong></p></td>
<td><p>None</p></td>
</tr>
</tbody>
</table>


## Definition

```xml
      <xs:complexType name="StartOrUpdateType">
         <xs:attribute name="Type" type="xs:string" use="required"/>
  
      </xs:complexType>
      
```

## Elements and attributes

### Child elements

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
<td><p><a href="from-element-startorupdatetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">From</a></p></td>
<td><p><a href="endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">EndPointType</a></p></td>
<td><p>Source of the media stream.</p></td>
</tr>
<tr class="even">
<td><p><a href="properties-element-startorupdatetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Properties</a></p></td>
<td><p><a href="startpropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">StartPropertiesType</a></p></td>
<td><p>Properties of the started or updated media stream.</p></td>
</tr>
<tr class="odd">
<td><p><a href="to-element-startorupdatetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">To</a></p></td>
<td><p><a href="endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">EndPointType</a></p></td>
<td><p>Destination of the media stream.</p></td>
</tr>
</tbody>
</table>


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
<td><p>Type</p></td>
<td><p>xs:string</p></td>
<td><p>required</p></td>
<td><p>Modality or media type for which the quality metrics are reported. The valid options are audio, video and applicationsharing</p></td>
<td><p>Values of the xs:string type.</p></td>
</tr>
</tbody>
</table>

