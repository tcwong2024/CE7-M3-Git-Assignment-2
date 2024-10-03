# CE7 M3 Git Assignment-2

## Github Authentication

GitHub authentication is the process of verifying a user's identity to allow access to GitHub resources, repositories, and services. It is crucial for managing permissions and ensuring secure interactions with GitHub. 

### There are several methods available for implementing authentication on GitHub:

|Methods| Description|
|-----|-----|
|**Username and Password** |•	**Basic Authentication**: Users can log in using their GitHub username and password. However, this method is less secure and is not recommended for API access.|
|**OAuth**|• **OAuth Apps**: You can use OAuth 2.0 to allow third-party applications to access your GitHub account without sharing your password. Users authorize the app, and the app receives an access token to perform actions on behalf of the user.<br> • **GitHub Apps**: Similar to OAuth Apps, but with more granular permissions and specific use cases. GitHub Apps can act on behalf of the user or the app itself.|
|**Personal Access Tokens** |•	**Token-Based Authentication**: Users can create personal access tokens that can be used instead of passwords for API requests or Git operations over HTTPS. These tokens can have specific scopes to limit permissions. |
|**SSH Keys** | •	**SSH Authentication**: Users can set up SSH keys for secure connections to GitHub repositories. This method is often used for cloning and pushing to repositories without entering a password.|
|**Two-Factor Authentication (2FA)** |•	**Two-Factor Authentication**: Users can enable 2FA for their GitHub accounts, adding an extra layer of security. This requires a second form of verification (e.g., a mobile app or SMS) in addition to the password. |
|**SAML Single Sign-On (SSO)** | •	**SAML SSO**: For organizations, GitHub supports SAML-based SSO, allowing users to authenticate through their organization’s identity provider. |
|**GitHub CLI Authentication** | •	**GitHub CLI**: Users can authenticate to GitHub using the GitHub Command Line Interface, which supports OAuth, personal access tokens, and SSH. |
