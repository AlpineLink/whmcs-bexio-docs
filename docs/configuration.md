---
layout: default
title: Configuration
nav_order: 3
---

# Configuration

This page covers the configuration options for the WHMCS ↔ Bexio Integration.

## API Credentials

### Bexio API Setup

1. Log in to your Bexio account and open [developer.bexio.com](https://developer.bexio.com/)
2. Go to Personal Access Tokens
3. Generate a new API key
4. Copy the API key to the module settings

{: .highlight }
**Note**: The Personal Access Token expires after 180 days. Make sure to set a reminder to renew it.

### WHMCS Settings

In the module configuration:

- **Bexio API Key**: Enter the key from Bexio
- **myAlpineLink License key**: Your personal License key

For troubleshooting common issues, see the [Troubleshooting](troubleshooting.md) page.

## Module Configuration

### Product Relations

Add your Product Relations to the Module.

1. Select whether you want to set a Relation for Domains or a Product within WHMCS

#### Product

1. Select the WHMCS Relation Product
2. Select the Product in Bexio.
3. Select the Account in Bexio.

#### Domain

1. Select one Domain or all Domains you want to set to this Product and Account in Bexio.

{: .note-title }
> Note
>
> You can also set a relation to all Domains in WHMCS.

2. Select the Product in Bexio.
3. Select the Account in Bexio.