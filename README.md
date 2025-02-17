# HubSpot Integrator for Dynamics 365

<div align="center">

[![GitHub Release](https://img.shields.io/github/v/release/novalogica/hubspot-integrator-for-dynamics-365)](https://github.com/novalogica/hubspot-integrator-for-dynamics-365/releases/tag/1.0.0)

[![Dataverse](https://img.shields.io/badge/Dataverse-gray.svg?logo=data:image/png;base64,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)](#)
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