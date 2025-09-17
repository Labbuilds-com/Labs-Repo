# Microsoft Graph API Projects

This directory contains various Microsoft Graph API sample applications and projects.

## 📁 Directory Structure

### C# Projects (`/csharp/`)

#### GraphUploadLargeAttachment
- **Description**: Console application for sending emails with large file attachments
- **Features**: 
  - Client credentials authentication flow
  - createUploadSession API for large files (3MB chunks)
  - Draft email creation and sending
  - Comprehensive error handling and progress tracking
- **Technology**: .NET 8.0, Microsoft Graph SDK, MSAL
- **Location**: `/csharp/GraphUploadLargeAttachment/`

## 🚀 Getting Started

Each project contains its own documentation:
- `README.md` - Project overview and instructions
- `CONFIG.md` - Configuration templates and setup guide
- `SETUP_GITHUB.md` - GitHub repository setup instructions

## 🔐 Security

All projects use placeholder credentials for security. See individual `CONFIG.md` files for setup instructions.

## 📖 Additional Resources

- [Microsoft Graph Documentation](https://docs.microsoft.com/en-us/graph/)
- [Microsoft Graph .NET SDK](https://github.com/microsoftgraph/msgraph-sdk-dotnet)
- [MSAL.NET Documentation](https://docs.microsoft.com/en-us/azure/active-directory/develop/msal-overview)