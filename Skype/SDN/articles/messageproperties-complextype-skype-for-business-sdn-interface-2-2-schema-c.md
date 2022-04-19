---
title: MessageProperties complexType (Schema C)
TOCTitle: MessageProperties complexType
ms:assetid: c077e1bb-e248-d481-726c-9516eacfd2f7
ms:mtpsurl: https://msdn.microsoft.com/library/Mt429356(v=office.16)
ms:contentKeyID: 68250798
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# MessageProperties complexType (Schema C)

(Skype for Business SDN Interface 2.2, Schema "C")

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
<td><p>SDNInterface.Schema.C.XSD</p></td>
</tr>
<tr class="odd">
<td><p><strong>Extension base</strong></p></td>
<td><p>None</p></td>
</tr>
</tbody>
</table>


## Definition

```xml
      <xs:complexType name="MessageProperties">
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

