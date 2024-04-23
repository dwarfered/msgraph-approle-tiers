# Microsoft Graph Application Role Tiers

As referenced by [EntraExplorer](https://www.entraexplorer.com/)

```typescript
export const AppRolePermissionLevels: Record<string, number> = {
    // Tier 0 - Risk to Core Platform Integrity
    "Application.ReadWrite.All": 0,
    "AppRoleAssignment.ReadWrite.All": 0,
    "Device.ReadWrite.All": 0,
    "Directory.ReadWrite.All": 0,
    "Group.ReadWrite.All": 0,
    "Mail.ReadWrite": 0,
    "Policy.ReadWrite.ConditionalAccess": 0,
    "PrivilegedAccess.ReadWrite.AzureAD": 0,
    "PrivilegedAccess.ReadWrite.AzureResources": 0,
    "RoleManagement.ReadWrite.Directory": 0,
    "UserAuthenticationMethod.ReadWrite.All": 0,
    "User.ReadWrite.All": 0,

    // Tier 1 - Risk to Organization
    "AuditLog.Read.All": 1,
    "Calendars.ReadWrite": 1,
    "Contacts.ReadWrite": 1,
    "ChannelMessage.Read.All": 1,
    "DeviceManagementApps.ReadWrite.All": 1,
    "DeviceManagementConfiguration.ReadWrite.All": 1,
    "DeviceManagementManagedDevice.ReadWrite.All": 1,
    "DeviceManagementServiceConfig.ReadWrite.All": 1,
    "Directory.Read.All": 1,
    "EntitlementManagement.ReadWrite.All": 1,
    "ExternalItem.ReadWrite.All": 1,
    "Files.ReadWrite.All": 1,
    "Files.Read.All": 1,
    "Group.Create": 1,
    "Group.Read.All": 1,
    "GroupMember.Read.All": 1,
    "GroupMember.ReadWrite.All": 1,
    "Mail.Send": 1,
    "Mail.Read": 1,
    "MailboxSettings.ReadWrite": 1,
    "OrgContact.Read.All": 1,
    "Policy.Read.All": 1,
    "SecurityEvents.Read.All": 1,
    "Sites.FullControl.All": 1,
    "Sites.Manage.All": 1,
    "Sites.Read.All": 1,
    "Sites.ReadWrite.All": 1,
    "User.Read.All": 1,
    "WindowsUpdates.ReadWrite.All": 1,
    
    // Tier 2 - Lower Risk 
};

```
