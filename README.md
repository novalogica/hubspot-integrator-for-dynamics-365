# HubSpot Integrator for Dynamics 365

<div align="center">

[![Release](https://img.shields.io/github/v/release/novalogica/hubspot-integrator-for-dynamics-365include_prereleases&sort=date&display_name=release&style=plastic)](https://github.com/novalogica/hubspot-integrator-for-dynamics-365/releases)

[![Dataverse](https://img.shields.io/badge/Dataverse-gray)](#)
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