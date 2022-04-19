---
title: Properties element (MessageType complexType) (Schema C)
TOCTitle: Properties element (MessageType complexType)
ms:assetid: 64e8b8be-9078-487d-1470-449b609feb5e
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404816(v=office.16)
ms:contentKeyID: 68250727
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Properties element (Schema C)

(MessageType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Details of the Error or reason for ending the streams.

**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<colgroup>
<col />
<col  />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p><a href="messageproperties-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">MessageProperties</a></p></td>
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
<td><p><a href="lyncdiagnostics-element-skype-for-business-sdn-interface-2-2-schema-c.md">LyncDiagnostics</a></p></td>
<td><p><a href="messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">MessageType</a></p></td>
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
<td><p><a href="msdiagnostics-element-messageproperties-complextype-skype-sdn-2-2-c.md">MSDiagnostics</a></p></td>
<td><p>xs:string</p></td>
<td><p>Skype for Business-specific diagnostics message.</p></td>
</tr>
<tr class="even">
<td><p><a href="msdiagnosticsclient-element-messageproperties-complextype-skype-sdn-2-2-c.md">MSDiagnosticsClient</a></p></td>
<td><p>Not defined</p></td>
<td><p>Skype for Business-specific diagnostics message from the client.</p></td>
</tr>
<tr class="odd">
<td><p><a href="msdiagnosticspublic-element-messageproperties-complextype-skype-sdn-2-2-c.md">MSDiagnosticsPublic</a></p></td>
<td><p>Not defined</p></td>
<td><p>Skype for Business-specific public diagnostics message.</p></td>
</tr>
<tr class="even">
<td><p><a href="responsecode-element-messageproperties-complextype-skype-sdn-2-2-c.md">ResponseCode</a></p></td>
<td><p><a href="responsecodetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">ResponseCodeType</a></p></td>
<td><p>Message describing the error.</p></td>
</tr>
</tbody>
</table>


### Attributes

None.

