---
title: Properties element (MessageType complexType) (Schema D)
TOCTitle: Properties element (MessageType complexType)
ms:assetid: 229119f1-87da-8ce4-ad6c-67404aad32fc
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170949(v=office.16)
ms:contentKeyID: 65855524
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Properties element (Schema D)

(MessageType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Details of the Error or reason for ending the streams.


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
<td><p><a href="messageproperties-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">MessageProperties</a></p></td>
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

    <xs:element name="Properties"  type="MessageProperties" minOccurs="0">
    
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
<td><p><a href="msdiagnostics-element-messageproperties-complextype-skype-sdn-2-2-d.md">MSDiagnostics</a></p></td>
<td><p>xs:string</p></td>
<td><p>Skype for Business-specific diagnostics message.</p></td>
</tr>
<tr class="even">
<td><p><a href="msdiagnosticsclient-element-messageproperties-complextype-skype-sdn-2-2-d.md">MSDiagnosticsClient</a></p></td>
<td><p>xs:string</p></td>
<td><p>Skype for Business-specific diagnostics message from the client.</p></td>
</tr>
<tr class="odd">
<td><p><a href="msdiagnosticspublic-element-messageproperties-complextype-skype-sdn-2-2-d.md">MSDiagnosticsPublic</a></p></td>
<td><p>xs:string</p></td>
<td><p>Skype for Business-specific public diagnostics message.</p></td>
</tr>
<tr class="even">
<td><p><a href="responsecode-element-messageproperties-complextype-skype-sdn-2-2-d.md">ResponseCode</a></p></td>
<td><p><a href="responsecodetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">ResponseCodeType</a></p></td>
<td><p>Message describing the error.</p></td>
</tr>
</tbody>
</table>


### Attributes

None.

