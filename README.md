# LockForge Password Manager

Secure desktop password manager with Dropbox sync and encryption.
Dropbox is required to run this program.

## Installation

1. Download `LockForge.zip` from the latest release and extract it
2. Install Dropbox and sign in
3. Run `LockForge.exe`

## Features

- 🔒 Encrypted password storage using Fernet
- 💾 Automatic Dropbox sync for cross-platform usage
- 🎯 Easy-to-use GUI interface
- 🔑 Password generator
- 📝 Account management tools

## Usage

### First Launch
- Application creates a `LockForge` folder in your Dropbox
- Generates encryption key automatically
- Sets up secure storage environment

### !!IMPORTANT!!
- **DO NOT** manually delete files in the 'LockForge' folder in Dropbox

### Main Functions

1. **Save Account**
   - Enter account details
   - Use password generator
   - Save encrypted data

2. **Manage Accounts**
   - View saved accounts
   - Retrieve credentials
   - Update information
   - Delete accounts

## Security

- Fernet symmetric encryption
- Local key storage
- Restricted file permissions
- No plaintext storage

## System Requirements

- Windows 10/11
- Dropbox account
- Internet connection for sync

## Troubleshooting

### Common Issues
- **Missing Files**: Wait for Dropbox to finish syncing
- **Icon not loading**: Reinstall application
- **Dropbox not found**: Install/login to Dropbox
- **Access denied**: Run as administrator

### Error Codes
- E001: Dropbox path not found
- E002: Encryption key error
- E003: File access denied

## Updates

Check releases page for latest version

## Developer

Morgan Rupert (Morgpo)
LinkedIn: https://www.linkedin.com/in/morgan-rupert-18804b2a9/
