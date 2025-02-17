# HubSpot Integrator for Dynamics 365

<div align="center">

[![GitHub Release](https://img.shields.io/github/v/release/novalogica/hubspot-integrator-for-dynamics-365)](https://github.com/novalogica/hubspot-integrator-for-dynamics-365/releases/tag/1.0.0)

[![Dataverse](https://img.shields.io/badge/Dataverse-gray.svg?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB3aWR0aD0iMjBweCIgaGVpZ2h0PSIxNXB4IiB2aWV3Qm94PSIwIDAgMTkgMTUiIHZlcnNpb249IjEuMSI+CjxkZWZzPgo8ZmlsdGVyIGlkPSJhbHBoYSIgZmlsdGVyVW5pdHM9Im9iamVjdEJvdW5kaW5nQm94IiB4PSIwJSIgeT0iMCUiIHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiPgogIDxmZUNvbG9yTWF0cml4IHR5cGU9Im1hdHJpeCIgaW49IlNvdXJjZUdyYXBoaWMiIHZhbHVlcz0iMCAwIDAgMCAxIDAgMCAwIDAgMSAwIDAgMCAwIDEgMCAwIDAgMSAwIi8+CjwvZmlsdGVyPgo8aW1hZ2UgaWQ9ImltYWdlMjciIHdpZHRoPSIxOSIgaGVpZ2h0PSIxNSIgeGxpbms6aHJlZj0iZGF0YTppbWFnZS9wbmc7YmFzZTY0LGlWQk9SdzBLR2dvQUFBQU5TVWhFVWdBQUFCTUFBQUFQQ0FZQUFBQUdSUFFzQUFBQUJtSkxSMFFBL3dEL0FQK2d2YWVUQUFBQlowbEVRVlE0amEzT1AwaWJZUlNGOGVlK1JnMytpMGlOSWlLWm9pQ29ZMm5yNUNCU0N0WXN0VkEzaFZEZEhLVWRkQkFFMGFWRE83UUthYWRJWm9sRnE2bVRHWVFxYVRjaENobWlyU2JCcFAydVEyZ3cwb0x3ZXNiRDVYZXVjQ1A2YS9zZTdpZFBNVjBQME1NT3FGTEVjNEt6L3BYTGFGanFKMUthSy9od3RiOUF4bHB3RnZkSjk0YWtOWjZSTXVpM040QnFFTDY1YjQ0VTA1ZkRtZnVBZWY4Y3dwNVNMY0VEMWlMQkVxYjU2Q1RTOCt6ZnlHM1NQR09LSHdVZjIwRUFyZjFHajJkcjBQaExPd2dRZDZjTDc4ZEJkS3ZCR2xQeEd2VDFRMnNJZ05NS0E1LzhkNE5OcFVVTEYxOGdhK3l4N0thQldzY2VBbVFsWmhCWHlsNGFUNU13R3k0MG1RRGE3TERsSmVuMjVRMzgyTEp5MUw4aWxiN1BBSVlkTnBIQTkvS0w4VFRPemh2b3kvMWZlWlJCcHVlbDZ1emQzMFlBTkRWUVIrUGVLUEtxRzNhUEtmaENVck9RMVBPM1hxcUhSekJEOTFHbkJmS0NkQjNoTk1TNFdJMUkwNStmMS9rcnN2bHpsYng0KzJnQUFBQUFTVVZPUks1Q1lJST0iLz4KPG1hc2sgaWQ9Im1hc2swIj4KICA8ZyBmaWx0ZXI9InVybCgjYWxwaGEpIj4KPHVzZSB4bGluazpocmVmPSIjaW1hZ2UyNyIvPgogIDwvZz4KPC9tYXNrPgo8bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhcjAiIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4MT0iMTI0LjY2NTAwMSIgeTE9IjM2LjI2NDk5OSIgeDI9IjE1NC4xMzIwMDQiIHkyPSIzMDMuNzMxOTk1IiBncmFkaWVudFRyYW5zZm9ybT0ibWF0cml4KDAuMDU1ODgyNCwwLDAsMC4wNTc0NzEzLDAsLTIuMjc1ODYyKSI+CjxzdG9wIG9mZnNldD0iMCIgc3R5bGU9InN0b3AtY29sb3I6cmdiKDMuNTI5NDEyJSw0MC4zOTIxNTclLDIxLjk2MDc4NCUpO3N0b3Atb3BhY2l0eToxOyIvPgo8c3RvcCBvZmZzZXQ9IjEiIHN0eWxlPSJzdG9wLWNvbG9yOnJnYigzLjkyMTU2OSUsMjkuODAzOTIyJSwxNy42NDcwNTklKTtzdG9wLW9wYWNpdHk6MTsiLz4KPC9saW5lYXJHcmFkaWVudD4KPGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXIxIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjI0NS45MzI5OTkiIHkxPSIzMi44NjcwMDEiIHgyPSIzMDEuNDY3MDEiIHkyPSIyOTguMDY2OTg2IiBncmFkaWVudFRyYW5zZm9ybT0ibWF0cml4KDAuMDU1ODgyNCwwLDAsMC4wNTc0NzEzLDAsLTIuMjc1ODYyKSI+CjxzdG9wIG9mZnNldD0iMCIgc3R5bGU9InN0b3AtY29sb3I6cmdiKDMwLjU4ODIzNSUsODEuNTY4NjI3JSwzOC40MzEzNzMlKTtzdG9wLW9wYWNpdHk6MTsiLz4KPHN0b3Agb2Zmc2V0PSIxIiBzdHlsZT0ic3RvcC1jb2xvcjpyZ2IoMTIuNTQ5MDIlLDYwLjc4NDMxNCUsMzAuNTg4MjM1JSk7c3RvcC1vcGFjaXR5OjE7Ii8+CjwvbGluZWFyR3JhZGllbnQ+CjxtYXNrIGlkPSJtYXNrMSI+CiAgPGcgZmlsdGVyPSJ1cmwoI2FscGhhKSI+CjxyZWN0IHg9IjAiIHk9IjAiIHdpZHRoPSIxOSIgaGVpZ2h0PSIxNSIgc3R5bGU9ImZpbGw6cmdiKDAlLDAlLDAlKTtmaWxsLW9wYWNpdHk6MC4yNTA5ODtzdHJva2U6bm9uZTsiLz4KICA8L2c+CjwvbWFzaz4KPGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXIyIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjI0NC45NTU5OTQiIHkxPSIzMDYuODgwMDA1IiB4Mj0iMjE2LjgzNCIgeTI9IjMwNi44ODAwMDUiIGdyYWRpZW50VHJhbnNmb3JtPSJtYXRyaXgoMC4wNDgzOTU1LDAuMDI4NzM1NiwtMC4wMjc5NDEyLDAuMDQ5NzcxNiwyLjUyNTAzLC04LjI1ODI2MykiPgo8c3RvcCBvZmZzZXQ9IjAiIHN0eWxlPSJzdG9wLWNvbG9yOnJnYigwJSwwJSwwJSk7c3RvcC1vcGFjaXR5OjE7Ii8+CjxzdG9wIG9mZnNldD0iMC4yNzIiIHN0eWxlPSJzdG9wLWNvbG9yOnJnYigwJSwwJSwwJSk7c3RvcC1vcGFjaXR5OjAuNTYwNzg0OyIvPgo8c3RvcCBvZmZzZXQ9IjAuNjIxIiBzdHlsZT0ic3RvcC1jb2xvcjpyZ2IoMCUsMCUsMCUpO3N0b3Atb3BhY2l0eTowLjI2NjY2NzsiLz4KPHN0b3Agb2Zmc2V0PSIxIiBzdHlsZT0ic3RvcC1jb2xvcjpyZ2IoMCUsMCUsMCUpO3N0b3Atb3BhY2l0eTowOyIvPgo8L2xpbmVhckdyYWRpZW50Pgo8Y2xpcFBhdGggaWQ9ImNsaXAyIj4KICA8cmVjdCB4PSIwIiB5PSIwIiB3aWR0aD0iMTkiIGhlaWdodD0iMTUiLz4KPC9jbGlwUGF0aD4KPGcgaWQ9InN1cmZhY2U2IiBjbGlwLXBhdGg9InVybCgjY2xpcDIpIj4KPHBhdGggc3R5bGU9IiBzdHJva2U6bm9uZTtmaWxsLXJ1bGU6bm9uemVybztmaWxsOnVybCgjbGluZWFyMik7IiBkPSJNIDEyLjExNzE4OCAtMC40MjE4NzUgTCAxMy40NzY1NjIgMC4zODY3MTkgTCAzLjgzNTkzOCAxNy41NjI1IEwgMi40NzI2NTYgMTYuNzU3ODEyIFogTSAxMi4xMTcxODggLTAuNDIxODc1ICIvPgo8L2c+CjxpbWFnZSBpZD0iaW1hZ2UyMyIgd2lkdGg9IjE5IiBoZWlnaHQ9IjE1IiB4bGluazpocmVmPSJkYXRhOmltYWdlL3BuZztiYXNlNjQsaVZCT1J3MEtHZ29BQUFBTlNVaEVVZ0FBQUJNQUFBQVBDQVlBQUFBR1JQUXNBQUFBQm1KTFIwUUEvd0QvQVArZ3ZhZVRBQUFCRzBsRVFWUTRqZTJSUFV2RFVCU0czNXZrSnVKSHNJdlVVbEQvZ2xBNmRITm9vWnNJUlJmQjBjbkpYOUhOUVhBVEhBTHU0dWFnaUVLSWJ1TGdFaEVFQlpzRXNibVgzQk1IRVJ4NmhNNzZ3bGtPUEEvdjRRQi9JdUtYdlE5Z0ZvQUh3QUpBQUJTQUJFQTZDbklZbVErZ3ZycTcxbTcxV2x2dXpFUXRHMlR4WlhCeGVMcDNjc2JKYkVaVzdXeDMyNTJkYmwvNnNsYTY1YVQwNWZ4Q2MybEZ2WC9jeGJkeE5BcXlHSm5YV0cvMGpDeGNKVFMrcDNBTGIzbXp1Y0V3N0ptV1UzSHJTbWlRSUJnUVNCQUlCTHRpVnprWjE0elNMSDFXMWxjai9hTmRNa2lleHBXcE1MZ09oaWJYU21nb1MwTUxoZHdNOCtnb091WmszQVB3R01adlpKY1AwNHRUYzhZaEozdko3c09EcS83TmZuZ080SlhqL2pOZVBnR1VuMjVBbnd5NytRQUFBQUJKUlU1RXJrSmdnZz09Ii8+CjxjbGlwUGF0aCBpZD0iY2xpcDEiPgogIDxyZWN0IHg9IjAiIHk9IjAiIHdpZHRoPSIxOSIgaGVpZ2h0PSIxNSIvPgo8L2NsaXBQYXRoPgo8ZyBpZD0ic3VyZmFjZTI2IiBjbGlwLXBhdGg9InVybCgjY2xpcDEpIj4KPHBhdGggc3R5bGU9IiBzdHJva2U6bm9uZTtmaWxsLXJ1bGU6ZXZlbm9kZDtmaWxsOnVybCgjbGluZWFyMCk7IiBkPSJNIDcuODE2NDA2IDEwLjQ3MjY1NiBDIDEwLjM5NDUzMSAxMi4wMDM5MDYgMTIuNzEwOTM4IDExLjQxMDE1NiAxNC4wMjM0MzggOS4wNzgxMjUgQyAxNS4zMzIwMzEgNi43NDYwOTQgMTQuODM5ODQ0IDMuNTYyNSAxMi40NjA5MzggMS41NzQyMTkgQyA5Ljg0NzY1NiAtMC42MDkzNzUgNS43NjE3MTkgLTAuNjIxMDk0IDIuNzQ2MDk0IDIuMTY3OTY5IEMgMC4wMzkwNjI1IDQuNjY3OTY5IC0wLjgwODU5NCA5LjA3ODEyNSAwLjc4NTE1NiAxMi44OTg0MzggQyAxLjA0Njg3NSAxMy41MTk1MzEgMS40OTYwOTQgMTQuMDM1MTU2IDIuMDY2NDA2IDE0LjM3MTA5NCBDIDMuNTQyOTY5IDE1LjI0NjA5NCA1LjQyNTc4MSAxNC43MjY1NjIgNi4yNzczNDQgMTMuMjEwOTM4IEwgNi4yODEyNSAxMy4yMTA5MzggWiBNIDcuODE2NDA2IDEwLjQ3MjY1NiAiLz4KPHBhdGggc3R5bGU9IiBzdHJva2U6bm9uZTtmaWxsLXJ1bGU6ZXZlbm9kZDtmaWxsOnVybCgjbGluZWFyMSk7IiBkPSJNIDE4LjE5OTIxOSAyLjEwOTM3NSBDIDE5Ljc4MTI1IDUuOTI1NzgxIDE4LjkzMzU5NCAxMC4zMjQyMTkgMTYuMjMwNDY5IDEyLjgyNDIxOSBDIDEzLjIxNDg0NCAxNS42MDkzNzUgOS4xMjg5MDYgMTUuNTk3NjU2IDYuNTE1NjI1IDEzLjQxNDA2MiBDIDQuMTM2NzE5IDExLjQyNTc4MSAzLjY0NDUzMSA4LjI0NjA5NCA0Ljk1MzEyNSA1LjkxMDE1NiBDIDYuMjYxNzE5IDMuNTc4MTI1IDguNTc4MTI1IDIuOTg4MjgxIDExLjE1NjI1IDQuNTE5NTMxIEwgMTIuNjk1MzEyIDEuNzgxMjUgQyAxMy41NDY4NzUgMC4yNjE3MTkgMTUuNDMzNTk0IC0wLjI1NzgxMiAxNi45MTAxNTYgMC42MjEwOTQgQyAxNy40ODQzNzUgMC45NjA5MzggMTcuOTM3NSAxLjQ4MDQ2OSAxOC4xOTkyMTkgMi4xMDkzNzUgIi8+CjxwYXRoIHN0eWxlPSIgc3Ryb2tlOm5vbmU7ZmlsbC1ydWxlOmV2ZW5vZGQ7ZmlsbDpyZ2IoMy4xMzcyNTUlLDUwLjU4ODIzOCUsMjUuODgyMzU0JSk7ZmlsbC1vcGFjaXR5OjE7IiBkPSJNIDExLjE1NjI1IDQuNTE5NTMxIEMgOC41NzgxMjUgMi45ODgyODEgNi4yNjE3MTkgMy41NzgxMjUgNC45NTMxMjUgNS45MTAxNTYgQyAzLjY4NzUgOC4xNjc5NjkgNC4xMDU0NjkgMTEuMjEwOTM4IDYuMjgxMjUgMTMuMjEwOTM4IEwgNy44MTY0MDYgMTAuNDcyNjU2IEMgMTAuMzk0NTMxIDEyLjAwMzkwNiAxMi43MTQ4NDQgMTEuNDEwMTU2IDE0LjAyMzQzOCA5LjA3ODEyNSBDIDE1LjI4OTA2MiA2LjgyNDIxOSAxNC44NzEwOTQgMy43NzczNDQgMTIuNjk1MzEyIDEuNzgxMjUgWiBNIDExLjE1NjI1IDQuNTE5NTMxICIvPgo8dXNlIHhsaW5rOmhyZWY9IiNzdXJmYWNlNiIgbWFzaz0idXJsKCNtYXNrMSkiLz4KPHVzZSB4bGluazpocmVmPSIjaW1hZ2UyMyIvPgo8L2c+CjwvZGVmcz4KPGcgaWQ9InN1cmZhY2UxIj4KPHVzZSB4bGluazpocmVmPSIjc3VyZmFjZTI2IiBtYXNrPSJ1cmwoI21hc2swKSIvPgo8L2c+Cjwvc3ZnPgo=)](#)
[![HubSpot](https://img.shields.io/badge/HubSpot-FF7A59?logo=hubspot&logoColor=fff)](#)

[![Power Apps](https://img.shields.io/badge/Power_Apps-purple)](#)
[![Power Automate](https://img.shields.io/badge/Power_Automate-blue)](#)
[![.NET](https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=fff)](#)
[![C#](https://custom-icon-badges.demolab.com/badge/C%23-%23239120.svg?logo=cshrp&logoColor=white)](#)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff)](#)
[![React](https://img.shields.io/badge/React-%2320232a.svg?logo=react&logoColor=%2361DAFB)](#)
[![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000?logo=shadcnui&logoColor=fff)](https://ui.shadcn.com/)
![HubSpot Integrator Banner](https://github.com/novalogica/hubspot-integrator-for-dynamics-365/blob/main/screenshots/HubSpot-Integrator-for-Dynamics-365.png?raw=true)

</div>

## 🎯 Overview

Our HubSpot Integrator for Dynamics 365 is designed to streamline and optimize your processes by enabling seamless data synchronization
between Dataverse and HubSpot. Unlike standard offerings, our solution offers unmatched flexibility and customization, allowing you to sync
any tables, standard or custom, and create custom mappings, supporting any data type columns. Whether you need one-way or two-way
synchronization, our intuitive interface ensures a quick and easy setup.

## 🌟 Key Features

### Core Capabilities
- **Universal Table Synchronization**: Sync any standard or custom table between platforms with comprehensive field mapping support
- **Flexible Sync Directions**: Configure one-way or bidirectional synchronization per table
- **Real-Time Updates**: Instantaneous data propagation with configurable sync intervals
- **Robust Error Handling**: Comprehensive error logging, notifications, and automatic retry mechanisms
- **Secure Architecture**: Self-contained solution with no external dependencies
- **Performance Optimization**: Intelligent batching and parallel processing for large datasets
- **Intuitive Setup**: User-friendly interface for quick and easy configuration.

### Business Benefits
- **Improved Data Accuracy**: Eliminate manual data entry and reduce errors
- **Enhanced Productivity**: Automate data synchronization across platforms
- **Better Decision Making**: Access consistent, up-to-date information across systems
- **Reduced Integration Costs**: Eliminate the need for custom development or third-party services
- **Quick Time-to-Value**: Intuitive setup process and ready-to-use configurations

## 📋 System Requirements

### Prerequisites
- Microsoft Dynamics 365 environment
- HubSpot account with API access (Marketing, Sales, or Service Hub)

## 🚀 Quick Start Guide

### 1. Installation
1. Download the latest release: [Download](https://github.com/novalogica/hubspot-integrator-for-dynamics-365/releases)
2. Import to your D365 Environment

### 2. Initial Setup
1. Access the HubSpot Integrator app in your Dynamics 365 environment
2. Configure your HubSpot API Key
4. Verify the connection status

### 3. Configure Your First Sync
1. Go to "Get Started."
2. Choose the table that you want to sync.
3. Select "Continue."
4. Click "Create Configurations."
5. Once the syncs are successfully created, click "Done."
6. If you want to map custom fields, edit the table sync. Otherwise, activate the table sync.

## ⚙️ Advanced Configuration

### Table Sync JSON Example
```json
{
  "d365Table": "contact",
  "hubspotTable": "contacts",
  "batchSize": 100,
  "integrationDirection": {
    "value": 1,
    "name": "➡️ Dataverse to HubSpot"
  },
  "attributeMappings": [
    {
      "attributes": {
        "d365": {
          "displayName": null,
          "logicalName": "firstname",
          "dataType": "String",
          "options": null
        },
        "hubspot": {
          "displayName": null,
          "logicalName": "firstname",
          "dataType": "text",
          "options": null
        },
        "isMatchingKey": false,
        "associationLabel": null,
        "defaultValue": null
      },
      "valueMappings": []
    },
    {
      "attributes": {
        "d365": {
          "displayName": null,
          "logicalName": "lastname",
          "dataType": "String",
          "options": null
        },
        "hubspot": {
          "displayName": null,
          "logicalName": "lastname",
          "dataType": "text",
          "options": null
        },
        "isMatchingKey": false,
        "associationLabel": null,
        "defaultValue": null
      },
      "valueMappings": []
    },
    {
      "attributes": {
        "d365": {
          "displayName": null,
          "logicalName": "emailaddress1",
          "dataType": "String",
          "options": null
        },
        "hubspot": {
          "displayName": null,
          "logicalName": "email",
          "dataType": "text",
          "options": null
        },
        "isMatchingKey": true,
        "associationLabel": null,
        "defaultValue": null
      },
      "valueMappings": []
    },
    {
      "attributes": {
        "d365": {
          "displayName": null,
          "logicalName": "mobilephone",
          "dataType": "String",
          "options": null
        },
        "hubspot": {
          "displayName": null,
          "logicalName": "mobilephone",
          "dataType": "phonenumber",
          "options": null
        },
        "isMatchingKey": false,
        "associationLabel": null,
        "defaultValue": null
      },
      "valueMappings": []
    }
  ],
  "dataFilter": null,
  "viewFilter": {
    "id": null,
    "name": null,
    "fetchXML": null
  }
}
```

## 🔍 Troubleshooting Guide

### Common Issues
1. **Connection Failures**
   - Verify API key validity
   - Check network connectivity

2. **Sync Errors**
   - Review field mapping compatibility
   - Check for required field values
   - Verify record ownership permissions

3. **Performance Issues**
   - Optimize batch sizes
   - Adjust sync frequencies
## 📈 Performance Optimization

### Best Practices
- Use batch processing for large datasets
- Implement efficient filtering
- Monitor system resources

### Monitoring Tools
- Real-time sync status monitoring
- Detailed error logging

## 📞 Support 

### Contact Information
**Address**: R. Nossa Sra. Fátima 14, 4420-214 S. Cosme, Porto, Portugal  
**Email**: info@novalogica.pt  
**Website**: [novalogica.pt](https://novalogica.pt)  
**LinkedIn**: [novalogica](https://linkedin.com/company/novalogica)

---

Made with ❤️ by novalogica in Porto, Portugal