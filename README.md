# Microsoft Entra ID Authentication & MFA

## Objective

Configure a phone authentication method in Microsoft Entra ID, troubleshoot a policy restriction, and verify that SMS authentication became usable.

## Step 1: Add a Phone Authentication Method

Added a phone authentication method to **Taylor Morgan's** account.

![](images/01-add-phone-authentication-method.png)

## Step 2: Identify the Policy Issue

Confirmed that the registered phone method was **Disabled by policy** and could not be used for authentication.

![](images/02-phone-method-disabled-by-policy.png)

## Step 3: Review Authentication Policies

Reviewed the user's evaluated authentication methods and confirmed that SMS was disabled.

![](images/03-authentication-methods-policy.png)

## Step 4: Review the Tenant SMS Policy

Opened the tenant authentication methods policy and verified that SMS authentication was disabled.

![](images/04-sms-policy-disabled.png)

## Step 5: Review SMS Settings

Reviewed the SMS policy configuration before making changes.

![](images/05-sms-settings-before-enable.png)

## Step 6: Enable SMS Authentication

Enabled SMS authentication for the lab environment.

![](images/06-sms-enabled-for-all-users.png)

## Step 7: Verify the Policy Change

Confirmed that SMS now appeared as an enabled authentication method for the user.

![](images/07-sms-policy-enabled.png)

## Step 8: Verify the Authentication Method

Confirmed that the phone number moved to **Usable authentication methods** and SMS was available for authentication.

![](images/08-sms-authentication-method-usable.png)

## Skills Demonstrated

- Microsoft Entra ID
- Multi-Factor Authentication (MFA)
- Authentication Method Management
- Authentication Policy Configuration
- IAM Troubleshooting
- Configuration Verification
