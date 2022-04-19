---
title: ResponseCode element (MessageProperties complexType) (Schema D)
TOCTitle: ResponseCode element (MessageProperties complexType)
ms:assetid: cef77f6d-f6c7-f1d3-8e6f-1859e1203576
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170987(v=office.16)
ms:contentKeyID: 65855562
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# ResponseCode element (MessageProperties complexType) (Schema D)

(MessageProperties complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Message describing the error.


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
<td><p><a href="responsecodetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">ResponseCodeType</a></p></td>
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

    <xs:element name="ResponseCode"  type="ResponseCodeType" minOccurs="0">
    
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
<td><p><a href="properties-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Properties</a></p></td>
<td><p><a href="messageproperties-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">MessageProperties</a></p></td>
<td><p>Details of the Error or reason for ending the streams.</p></td>
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
<td><p>Code</p></td>
<td><p>xs:unsignedShort</p></td>
<td><p>required</p></td>
<td><p>SIP error code for this error.</p></td>
<td><p>Values of the xs:unsignedShort type.</p></td>
</tr>
</tbody>
</table>

