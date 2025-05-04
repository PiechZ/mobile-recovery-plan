# WatchGuard AuthPoint Recovery Guide

This guide provides steps to recover access to your accounts when you lose your device with WatchGuard AuthPoint installed.

## Immediate Actions

1. **Contact Your IT Administrator**
   - If AuthPoint is used for work access, contact your IT department immediately
   - They can help reset your device enrollment or provide temporary access
   - Be prepared to verify your identity through company procedures

2. **Use Alternative Authentication Methods**
   - If configured, use temporary access options:
     - SMS-based one-time passwords
     - Email recovery options
     - Backup verification codes if previously provided

3. **Check for Self-Service Recovery Options**
   - Some organizations configure self-service recovery in AuthPoint
   - Check your company's IT portal for self-service options
   - You may need your username and a secondary verification method

## Recovery Process

1. **Device Re-enrollment**
   - Download WatchGuard AuthPoint on your new device from [Google Play Store](https://play.google.com/store/apps/details?id=com.watchguard.authpoint) or [Apple App Store](https://apps.apple.com/us/app/watchguard-authpoint/id1335115425)
   - Your administrator will need to:
     - Disable your old device in the AuthPoint management portal
     - Send you a new activation QR code or activation link

2. **Activation Process**
   - Open AuthPoint on your new device
   - Scan the QR code provided by your administrator or use the activation link
   - Follow the on-screen instructions to complete enrollment
   - Create a new PIN for the app if required

3. **Testing the Configuration**
   - After setup, test authentication with a non-critical service
   - Verify that push notifications are working properly
   - Ensure OTP (One-Time Password) generation works correctly

## Using the Cloud Backup Feature (If Enabled)

1. **Restore from Cloud Backup**
   - If your organization enabled cloud backup for AuthPoint:
     - Install AuthPoint on your new device
     - Sign in with the same Apple ID/Google account used previously
     - When prompted, choose to restore from backup
     - Verify with required credentials

2. **Verify Restoration**
   - Check that all your AuthPoint-protected resources appear
   - Confirm that your user profile and settings are restored
   - Test authentication for a few services

## Preventive Measures for the Future

1. **Enable Backup if Available**
   - If your organization allows cloud backup for AuthPoint:
     - Go to Settings in the AuthPoint app
     - Enable the backup option if available
     - Ensure your cloud account (Google/Apple) is properly set up

2. **Document Your Setup**
   - Keep a record of which services use AuthPoint for authentication
   - Note the contact information for your IT support team
   - Store this information securely but accessible without your phone

3. **Set Up Multiple Authentication Methods**
   - Where allowed by your organization, configure additional recovery methods:
     - Recovery email
     - Secondary phone number
     - Backup verification codes

4. **Consider Hardware Tokens**
   - For critical access, ask if your organization supports hardware tokens
   - These physical devices can serve as backup when your phone is unavailable

## Special Considerations

1. **Temporary Access Procedures**
   - Some organizations have specific procedures for temporary access
   - This might include time-limited bypass codes or in-person verification
   - Familiarize yourself with your organization's specific policies

2. **Multi-User Resources**
   - If you're responsible for shared resources:
     - Ensure other authorized users can still access these resources
     - Notify colleagues if your authentication issues might affect their work

3. **VPN and Remote Access**
   - If AuthPoint secures your VPN access:
     - Have alternative work arrangements ready during recovery
     - Test your VPN connection immediately after recovery is complete

By following these steps and working with your IT department, you can quickly recover access to resources protected by WatchGuard AuthPoint after losing your device.
