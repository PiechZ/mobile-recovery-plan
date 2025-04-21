# Duo Mobile Recovery Guide

This guide provides steps to recover access to your accounts when you lose your device with Duo Mobile installed.

## Immediate Actions

1. **Contact Your IT Administrator (For Work Accounts)**
   - If Duo is used for workplace access, contact your IT department immediately
   - They can temporarily bypass Duo or help reset your device enrollment
   - Provide verification of your identity as required by your organization

2. **Use Backup Methods for Personal Accounts**
   - Use backup codes provided when you set up Duo on personal accounts
   - Check for alternative 2FA methods you may have configured (SMS, email)
   - Some services allow you to receive a code via phone call

3. **Download Duo Mobile on Your New Device**
   - Install from [Google Play Store](https://play.google.com/store/apps/details?id=com.duosecurity.duomobile) or [Apple App Store](https://apps.apple.com/us/app/duo-mobile/id422663827)

## Restoring Your Accounts

1. **For Work/Organization Accounts**
   - Follow your organization's specific process for re-enrolling a device
   - Typically requires:
     - Assistance from IT administrator
     - Identity verification
     - New activation link or QR code
   - You may receive an enrollment email or need to log in to a self-service portal

2. **For Personal Accounts**
   - Log in to each service using backup codes or alternative methods
   - Navigate to security settings
   - Remove the old Duo device
   - Re-enroll your new device by scanning a new QR code
   - This must be done individually for each service

3. **Using Duo Restore (If Previously Backed Up)**
   - If you had enabled Duo Restore before losing your device:
     - Install Duo Mobile on your new device
     - When prompted to "Add Account," choose "I have an existing account"
     - Sign in with the Google or Apple account used for backup
     - Follow prompts to restore your accounts

## Preventive Measures for the Future

1. **Enable Duo Restore**
   - In Duo Mobile, go to Settings
   - Enable "Duo Restore" and link to your Google or Apple account
   - This backs up your Duo-protected accounts (encrypted)

2. **Save Backup Codes**
   - When enabling Duo for any service, save the provided backup codes
   - Store these in a secure location separate from your phone
   - Label clearly which service each set of codes belongs to

3. **Set Up Multiple Authentication Methods**
   - Where available, configure additional recovery methods:
     - Backup phone numbers
     - Hardware tokens (like YubiKey)
     - Backup email addresses

4. **Document Your Duo-Protected Services**
   - Keep a secure list of which services use Duo Mobile
   - Include contact information for support for each service
   - Note any special recovery procedures

## Special Considerations

1. **Hardware Tokens as Backup**
   - Consider purchasing a hardware token (like YubiKey) as a backup
   - Many organizations and services support these as alternatives to app-based authentication

2. **Organization-Specific Policies**
   - Be aware that organizations may have different policies for lost devices
   - Some may require additional verification steps
   - Some may have waiting periods for security reasons

3. **Timing Considerations**
   - Account recovery involving IT departments may not be immediate
   - Plan for potential delays in access to critical systems
   - Have alternative work arrangements ready if needed
