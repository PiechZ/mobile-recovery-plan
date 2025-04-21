# ESET Authenticator Recovery Guide

This guide provides steps to recover access to your accounts when you lose your device with ESET Authenticator installed.

## Immediate Actions

1. **Use Backup Codes for Account Access**
   - For each service protected by ESET Authenticator, use the backup codes provided when you set up 2FA
   - These codes should have been saved in a secure location separate from your phone
   - Most services typically provide 8-10 single-use backup codes

2. **Use Alternative Recovery Methods**
   - Check for alternative 2FA methods you may have enabled:
     - SMS verification
     - Email recovery
     - Security questions
   - These can provide temporary access to disable the lost authenticator

3. **Download ESET Authenticator on New Device**
   - Install from [Google Play Store](https://play.google.com/store/apps/details?id=com.eset.esa) or [Apple App Store](https://apps.apple.com/us/app/eset-secure-authentication/id1080074683)

## Restoring Your Accounts

1. **Restore from ESET Secure Backup (If Enabled)**
   - If you previously enabled encrypted cloud backup:
     - Install ESET Authenticator on your new device
     - Tap the menu (three dots) and select "Settings"
     - Select "Secure backup"
     - Log in with your ESET Account
     - Choose to restore your accounts
     - Verify with your backup password

2. **Manual Account Recovery Process**
   - If backup wasn't enabled or isn't working:
     - Log into each service using backup codes or alternative methods
     - Navigate to security/2FA settings
     - Remove the old ESET Authenticator connection
     - Set up 2FA again with your new installation of ESET Authenticator
     - Scan the new QR code provided by each service

3. **Verify Recovery Success**
   - Ensure all accounts appear in your new ESET Authenticator app
   - Test authentication for your most critical accounts
   - Verify that time-based codes are working correctly

## Preventive Measures for the Future

1. **Enable Secure Backup**
   - In ESET Authenticator, go to menu (three dots) → Settings
   - Select "Secure backup"
   - Create an ESET Account if you don't have one
   - Set a strong backup password (different from your ESET account password)
   - Enable automatic backups

2. **Export Account Data As Backup**
   - Periodically export your accounts as an encrypted file
   - Menu (three dots) → Settings → Import/Export
   - Store the encrypted export file securely
   - Remember the password used for encryption

3. **Save Backup Codes**
   - When setting up 2FA with any service, save the provided backup codes
   - Store these codes in a secure location (password manager, secure note, physical safe)
   - Consider multiple storage locations for critical accounts

4. **Document Your Setup**
   - Keep a secure record of which accounts use ESET Authenticator
   - Include recovery information for each service
   - Store this documentation securely and separately from your device

## Security Best Practices

1. **Backup Password Management**
   - Use a strong, unique password for your ESET Secure Backup
   - Store this password securely but separately from your backup codes
   - Consider using a password manager for this purpose

2. **Regular Verification**
   - Periodically check that your backup is current and functioning
   - Test the restoration process on a secondary device if possible
   - Update your backup after adding new accounts

3. **Multiple Authentication Methods**
   - Where possible, configure multiple 2FA methods for critical accounts
   - This provides redundancy if one method becomes unavailable
