# HubSpot Integrator for Dataverse

<div align="center">

[![Release](https://img.shields.io/github/v/release/novalogica/hubspot-integrator-for-dynamics-365include_prereleases&sort=date&display_name=release&style=plastic)](https://github.com/novalogica/hubspot-integrator-for-dynamics-365/releases)
[![Dataverse](https://img.shields.io/badge/Dataverse-gray.svg?logo=data:image/svg%2bxml;base64,PHN2ZyBmaWxsPSJub25lIiBoZWlnaHQ9IjI2MC44MTY0NyIgdmlld0JveD0iMCAwIDMzOS44NTY2NiAyNjAuODE2NDciIHdpZHRoPSIzMzkuODU2NjYiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiPjxmaWx0ZXIgaWQ9ImEiIGNvbG9yLWludGVycG9sYXRpb24tZmlsdGVycz0ic1JHQiIgZmlsdGVyVW5pdHM9InVzZXJTcGFjZU9uVXNlIiBoZWlnaHQ9IjEyNy42MTEiIHdpZHRoPSIxMjcuNjExIiB4PSIxMDUuOTk4IiB5PSIxMDcuMjA4Ij48ZmVGbG9vZCBmbG9vZC1vcGFjaXR5PSIwIiByZXN1bHQ9IkJhY2tncm91bmRJbWFnZUZpeCIvPjxmZUNvbG9yTWF0cml4IGluPSJTb3VyY2VBbHBoYSIgdHlwZT0ibWF0cml4IiB2YWx1ZXM9IjAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDEyNyAwIi8+PGZlT2Zmc2V0IGR5PSIuMTkiLz48ZmVHYXVzc2lhbkJsdXIgc3RkRGV2aWF0aW9uPSIuMTkiLz48ZmVDb2xvck1hdHJpeCB0eXBlPSJtYXRyaXgiIHZhbHVlcz0iMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMC4yNCAwIi8+PGZlQmxlbmQgaW4yPSJCYWNrZ3JvdW5kSW1hZ2VGaXgiIG1vZGU9Im5vcm1hbCIgcmVzdWx0PSJlZmZlY3QxX2Ryb3BTaGFkb3ciLz48ZmVDb2xvck1hdHJpeCBpbj0iU291cmNlQWxwaGEiIHR5cGU9Im1hdHJpeCIgdmFsdWVzPSIwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAxMjcgMCIvPjxmZU9mZnNldCBkeT0iMSIvPjxmZUdhdXNzaWFuQmx1ciBzdGREZXZpYXRpb249IjIiLz48ZmVDb2xvck1hdHJpeCB0eXBlPSJtYXRyaXgiIHZhbHVlcz0iMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMCAwIDAgMC4zMiAwIi8+PGZlQmxlbmQgaW4yPSJlZmZlY3QxX2Ryb3BTaGFkb3ciIG1vZGU9Im5vcm1hbCIgcmVzdWx0PSJlZmZlY3QyX2Ryb3BTaGFkb3ciLz48ZmVCbGVuZCBpbj0iU291cmNlR3JhcGhpYyIgaW4yPSJlZmZlY3QyX2Ryb3BTaGFkb3ciIG1vZGU9Im5vcm1hbCIgcmVzdWx0PSJzaGFwZSIvPjwvZmlsdGVyPjxsaW5lYXJHcmFkaWVudCBpZD0iYiIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiIHgxPSIxMjQuNjY1IiB4Mj0iMTU0LjEzMiIgeTE9IjM2LjI2NTIwMiIgeTI9IjMwMy43MzE5OSI+PHN0b3Agb2Zmc2V0PSIwIiBzdG9wLWNvbG9yPSIjMDk2NzM4Ii8+PHN0b3Agb2Zmc2V0PSIxIiBzdG9wLWNvbG9yPSIjMGE0YzJkIi8+PC9saW5lYXJHcmFkaWVudD48bGluZWFyR3JhZGllbnQgaWQ9ImMiIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4MT0iMjQ1LjkzMyIgeDI9IjMwMS40NjcwMSIgeTE9IjMyLjg2NzI5OCIgeTI9IjI5OC4wNjY5OSI+PHN0b3Agb2Zmc2V0PSIwIiBzdG9wLWNvbG9yPSIjNGVkMDYyIi8+PHN0b3Agb2Zmc2V0PSIxIiBzdG9wLWNvbG9yPSIjMjA5YjRlIi8+PC9saW5lYXJHcmFkaWVudD48bGluZWFyR3JhZGllbnQgaWQ9ImQiIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4MT0iMjQ0Ljk1NTk5IiB4Mj0iMjE2LjgzNCIgeTE9IjMwNi44OCIgeTI9IjMwNi44OCI+PHN0b3Agb2Zmc2V0PSIwIi8+PHN0b3Agb2Zmc2V0PSIuMjcxOTMyIiBzdG9wLW9wYWNpdHk9Ii41NjA2NjEiLz48c3RvcCBvZmZzZXQ9Ii42MjA4OTYiIHN0b3Atb3BhY2l0eT0iLjI2NDUxOCIvPjxzdG9wIG9mZnNldD0iMSIgc3RvcC1vcGFjaXR5PSIwIi8+PC9saW5lYXJHcmFkaWVudD48bGluZWFyR3JhZGllbnQgaWQ9ImUiIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4MT0iMjI5LjYwOCIgeDI9IjE4Ni4zMzQiIHkxPSIyMjkuODE3OTkiIHkyPSI5NS42Njk4Ij48c3RvcCBvZmZzZXQ9IjAiIHN0b3AtY29sb3I9IiM2NmViNmUiLz48c3RvcCBvZmZzZXQ9IjEiIHN0b3AtY29sb3I9IiM5ZmUwYTIiLz48L2xpbmVhckdyYWRpZW50PjxjbGlwUGF0aCBpZD0iZiI+PHBhdGggZD0ibTAgMGgzNDB2MzQwaC0zNDB6Ii8+PC9jbGlwUGF0aD48Y2xpcFBhdGggaWQ9ImciPjxwYXRoIGQ9Im0wIDBoMzQwdjM0MGgtMzQweiIvPjwvY2xpcFBhdGg+PG1hc2sgaWQ9ImgiIGhlaWdodD0iMjYyIiBtYXNrVW5pdHM9InVzZXJTcGFjZU9uVXNlIiB3aWR0aD0iMzQxIiB4PSItMSIgeT0iMzkiPjxwYXRoIGQ9Im0zMjUuNjc0IDc2LjMwMzQtLjAxMS0uMDAwNmMtNC41MzYtMTAuNTM2NS0xMi4zODQtMTkuNzU0My0yMy4wODItMjUuOTMxLTI2LjM5NS0xNS4yMzg4LTYwLjE0NS02LjE5NjUtNzUuMzg1IDIwLjE5NjNsLS4wMTUtLjAwMDljLTEuMzY2LTEuMjE4OC0yLjc3Mi0yLjQxMy00LjIxNS0zLjU4NTYtNDYuNzY4LTM3Ljk5My0xMTkuODkyLTM4LjE2MzItMTczLjgxNjQgMTAuMzEwMS00OC40MzkxNDkgNDMuNTQyMy02My41OTMyIDEyMC4yNjAzLTM1LjExOTkgMTg2Ljc0MDNsLjAxNzYuMDAxYzQuNTU2NiAxMC40MDIgMTIuMzUzIDE5LjQ5NCAyMi45NDE1IDI1LjYwOCAyNi4zODYgMTUuMjMzIDYwLjEyMjggNi4yMDIgNzUuMzcwMi0yMC4xNzFsLjAxNS4wMDEuMDE0LS4wMjRjMS4zNjUgMS4yMTkgMi43NyAyLjQxNSA0LjIxMyAzLjU4OCA0Ni43NjggMzcuOTkzIDExOS44OTIgMzguMTYzIDE3My44MTYtMTAuMzEgNDguMzYyLTQzLjQ3MyA2My41NDUtMTIwLjAxNSAzNS4yNTctMTg2LjQyMTZ6IiBmaWxsPSIjYzRjNGM0Ii8+PC9tYXNrPjxnIGNsaXAtcGF0aD0idXJsKCNmKSIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCAtMzkuNjAwMDM1KSI+PGcgY2xpcC1wYXRoPSJ1cmwoI2cpIj48ZyBtYXNrPSJ1cmwoI2gpIj48ZyBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGZpbGwtcnVsZT0iZXZlbm9kZCI+PHBhdGggZD0ibTEzOS45MDIgMjIxLjc5OGM0Ni4xMzYgMjYuNjM2IDg3LjU5IDE2LjM2IDExMS4wMzItMjQuMjQyIDIzLjQ0Mi00MC42MDMgMTQuNjI4LTk1Ljk2OC0yNy45NjYtMTMwLjU3MDYtNDYuNzY4LTM3Ljk5My0xMTkuODkyLTM4LjE2MzMtMTczLjgxNjYgMTAuMzEtNDguNDM5MDk2IDQzLjU0MjYtNjMuNTkzMSAxMjAuMjYwNi0zNS4xMTk5IDE4Ni43NDA2bC4wMTQ4LjAwMWM0LjU1NjcgMTAuNDAxIDEyLjM1MyAxOS40OTQgMjIuOTQxNiAyNS42MDcgMjYuMzg2IDE1LjIzNCA2MC4xMjI4IDYuMjAzIDc1LjM3MDEtMjAuMTdoLjAxOHoiIGZpbGw9InVybCgjYikiLz48cGF0aCBkPSJtMzI1LjY2MiA3Ni4zMDI4LjAxMy4wMDA4YzI4LjI4OSA2Ni40MDY0IDEzLjEwNiAxNDIuOTQ4NC0zNS4yNTYgMTg2LjQyMTQtNTMuOTI1IDQ4LjQ3My0xMjcuMDQ4IDQ4LjMwMy0xNzMuODE2IDEwLjMxLTQyLjU5NDUtMzQuNjAzLTUxLjQwOC04OS45NjgtMjcuOTY2MS0xMzAuNTcgMjMuNDQyMS00MC42MDMgNjQuODk1MS01MC44Nzg1IDExMS4wMzExLTI0LjI0MmwyNy41MTQtNDcuNjU1Ni4wMTUuMDAwOGMxNS4yNDEtMjYuMzkxNSA0OC45OS0zNS40MzMgNzUuMzg0LTIwLjE5NDUgMTAuNjk3IDYuMTc2MyAxOC41NDUgMTUuMzkzNCAyMy4wODEgMjUuOTI5MXoiIGZpbGw9InVybCgjYykiLz48cGF0aCBkPSJtMTk5LjY2OSAxMTguMjI2Yy00Ni4xMzYtMjYuNjM2OS04Ny41OS0xNi4zNjEtMTExLjAzMTggMjQuMjQxLTIyLjY0OCAzOS4yMjgtMTUuMTg4NCA5Mi4yMzUgMjMuNzU0OCAxMjYuOTg1bDI3LjUxMi00Ny42NTNjNDYuMTM2IDI2LjYzNyA4Ny41OSAxNi4zNjEgMTExLjAzMS0yNC4yNDEgMjIuNjQ4LTM5LjIyOCAxNS4xODktOTIuMjM1LTIzLjc1NC0xMjYuOTg1eiIgZmlsbD0iIzA4ODE0MiIvPjwvZz48cGF0aCBkPSJtMjE2LjgzNCAzMi4yNjg5MDJoMjguMTIxOTAxdjM0NS4xMjIwMWgtMjguMTIxOTAxeiIgZmlsbD0idXJsKCNkKSIgb3BhY2l0eT0iLjI1IiB0cmFuc2Zvcm09Im1hdHJpeCguODY2MDI1NCAuNSAtLjUgLjg2NjAyNTQgNDUuMTg0Njk4IC0xMDQuMDkzNzg3KSIvPjxnIGZpbHRlcj0idXJsKCNhKSI+PHBhdGggZD0ibTIyMS41ODcgMTk5LjkxMWMtMTYuNTEyIDI4LjU5OS01My4wODIgMzguMzk4LTgxLjY4MSAyMS44ODYtMjguNi0xNi41MTItMzguMzk5LTUzLjA4Mi0yMS44ODctODEuNjgyIDE2LjUxMi0yOC41OTkgNTMuMDgyLTM4LjM5OCA4MS42ODItMjEuODg2IDI4LjU5OSAxNi41MTIgMzguMzk4IDUzLjA4MiAyMS44ODYgODEuNjgyeiIgZmlsbD0idXJsKCNlKSIvPjwvZz48L2c+PC9nPjwvZz48L3N2Zz4=)](#)
[![HubSpot](https://img.shields.io/badge/HubSpot-FF7A59?logo=hubspot&logoColor=fff)](#)

[![Power Apps](https://img.shields.io/badge/Power_Apps-purple)](#)
[![Power Automate](https://img.shields.io/badge/Power_Automate-blue)](#)
[![.NET](https://img.shields.io/badge/.NET_4.6.2-512BD4?logo=dotnet&logoColor=fff)](#)
[![C#](https://custom-icon-badges.demolab.com/badge/C%23-%23239120.svg?logo=cshrp&logoColor=white)](#)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff)](#)
[![React](https://img.shields.io/badge/React-%2320232a.svg?logo=react&logoColor=%2361DAFB)](#)
[![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000?logo=shadcnui&logoColor=fff)](#)
![HubSpot Integrator Banner](https://github.com/novalogica/hubspot-integrator-for-dynamics-365/blob/main/screenshots/HubSpot-Integrator-for-Dynamics-365.png?raw=true)

</div>

## 🎯 Overview

Our HubSpot Integrator for Dataverse is designed to streamline and optimize your processes by enabling seamless data synchronization
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
- Microsoft Dataverse environment
- HubSpot account with API access (Marketing, Sales, or Service Hub)

## 🚀 Quick Start Guide

### 1. Installation
1. Download the latest release: [Download]()
2. Import to your D365 Environment

### 2. Initial Setup
1. Access the HubSpot Integrator app in your Dataverse environment
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


## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for full details.

## 📞 Support 

### Contact Information
**Address**: R. Nossa Sra. Fátima 14, 4420-214 S. Cosme, Porto, Portugal  
**Email**: info@novalogica.pt  
**Website**: [novalogica.pt](https://novalogica.pt)  
**LinkedIn**: [novalogica](https://linkedin.com/company/novalogica)

---

Made with ❤️ by novalogica in Porto, Portugal