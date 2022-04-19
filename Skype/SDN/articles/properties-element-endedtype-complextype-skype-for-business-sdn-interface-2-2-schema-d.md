---
title: Properties element (EndedType complexType) (Schema D)
TOCTitle: Properties element (EndedType complexType)
ms:assetid: 7a607432-3307-04e8-04b7-916390c2ca3e
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170951(v=office.16)
ms:contentKeyID: 65855525
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Properties element (Schema D)

(EndedType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Properties of the Error.


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
<td><p><a href="endedproperties-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">EndedProperties</a></p></td>
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

    <xs:element name="Properties"  type="EndedProperties" minOccurs="0">
    
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
<td><p><a href="ended-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Ended</a></p></td>
<td><p><a href="endedtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">EndedType</a></p></td>
<td><p>Event that a Sip call has ended and all media stream terminated.</p></td>
</tr>
</tbody>
</table>


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
<td><p><a href="msdiagnostics-element-endedproperties-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">MSDiagnostics</a></p></td>
<td><p>xs:string</p></td>
<td><p>More info related to the error.</p></td>
</tr>
<tr class="even">
<td><p><a href="msdiagnosticsclient-element-endedproperties-complextype-skype-sdn-2-2-d.md">MSDiagnosticsClient</a></p></td>
<td><p>xs:string</p></td>
<td><p>Info about the error related to and reported by the client.</p></td>
</tr>
<tr class="odd">
<td><p><a href="msdiagnosticspublic-element-endedproperties-complextype-skype-sdn-2-2-d.md">MSDiagnosticsPublic</a></p></td>
<td><p>xs:string</p></td>
<td><p>Public info about the error.</p></td>
</tr>
</tbody>
</table>


### Attributes

None.

