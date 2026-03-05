---
layout: default
title: Installation and Setup
nav_order: 2
---

# Installation and Setup

This guide will walk you through the installation and initial setup of the WHMCS ↔ Bexio Integration.

## Prerequisites

Before installing the integration, ensure you have:

- WHMCS installed and configured
- A Bexio account with API access
- PHP 7.4 or higher
- cURL extension enabled
- A backup of your WHMCS files and database

## Downloading the Module

1. Download the latest version of the WHMCS ↔ Bexio Integration module from myAlpineLink.
2. Extract the files to your WHMCS modules directory.

## Installation Steps

1. Upload the module files to `your-whmcs-path/modules/addons/bexio/` and `your-whmcs-path/includes/hooks/`
2. Go to WHMCS Admin > Setup > Addon Modules
3. Activate the "WHMCS Bexio Integration" module
4. Configure the API credentials (see Configuration section)
5. Add your License key

## Initial Configuration

After installation, you need to:

1. Enter your Bexio API key
2. Set up synchronization settings
3. Test the connection

For detailed configuration options, see the [Configuration](configuration.md) page.