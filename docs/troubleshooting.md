---
layout: default
title: Troubleshooting
nav_order: 4
---

# Troubleshooting

Common issues and solutions for the WHMCS ↔ Bexio Integration.

## Connection Issues

### API Key Invalid

**Error**: "Invalid API key"

**Solution**:
- Verify the API key in Bexio settings
- Ensure the key has the correct permissions
- Regenerate the key if necessary

### Network Errors

**Error**: "Connection timeout" or "cURL error"

**Solution**:
- Check firewall settings
- Ensure outbound connections to Bexio are allowed
- Verify DNS resolution

## Synchronization Problems

### Data Not Syncing

**Symptoms**: Changes not appearing in the other system

**Solution**:
- Check sync logs for errors
- Verify data mapping configuration
- Ensure both systems are online

### Duplicate Records

**Issue**: Duplicate customers or invoices

**Solution**:
- Review deduplication settings
- Manually merge duplicates
- Adjust sync filters

## Common Errors

### "Permission denied"

- Verify WHMCS admin permissions
- Check Bexio user roles

## Logs and Debugging

Enable debug logging in the module settings to get more detailed error information.

## Product Relation

No Product Relation has been configured. Please go to the Bexio Integration Settings page and add your Product Relation.

## Support

If issues persist, contact support with:
- Error messages
- Log files
- Configuration screenshots