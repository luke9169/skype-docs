---
title: Route element (MessageType complexType) (Schema D)
TOCTitle: Route element (MessageType complexType)
ms:assetid: 031bb522-650f-fe6f-0dfd-a93c228cf5b1
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170989(v=office.16)
ms:contentKeyID: 65855565
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Route element (MessageType complexType)  (Schema D)

(MessageType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Network path of the media stream only provided in Skype for Business 2013 and when the traceRoute feature is activated in Skype for Business.


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
<td><p><a href="routetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">RouteType</a></p></td>
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

    <xs:element name="Route"  type="RouteType" minOccurs="0">
    
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
<td><p><a href="lyncdiagnostics-element-skype-for-business-sdn-interface-2-2-schema-d.md">LyncDiagnostics</a></p></td>
<td><p><a href="messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">MessageType</a></p></td>
<td><p>The root element for output from the Skype for Business SDN Manager.</p></td>
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
<td><p><a href="hop-element-routetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Hop</a></p></td>
<td><p>xs:string</p></td>
<td><p>IP address of one hop (router, gateway, switch, etc) on the path from the source to the destination of the media stream.</p></td>
</tr>
</tbody>
</table>


### Attributes

None.

