# Privacy Policy for SnapQraft Chrome Extension

**Last Updated:** 29/06/2025

## 1. Introduction

This Privacy Policy describes how SnapQraft ("we," "our," or "us") collects, uses, and protects your information when you use our Chrome extension. SnapQraft is a QR code generation and scanning tool that allows users to create customized QR codes from web pages and scan existing QR codes.

## 2. Information We Collect

### 2.1 Information You Provide
- **URLs**: When you generate QR codes, we process the URLs of web pages you visit to create QR codes. These URLs are temporarily stored locally on your device.
- **QR Code Customization Settings**: Your preferences for QR code styling, colors, sizes, and logos are stored locally on your device.
- **QR Code History**: A local history of generated and scanned QR codes is maintained on your device (limited to the last 50 items).

### 2.2 Information Collected Automatically
- **Active Tab Information**: We access the URL of your currently active browser tab to generate QR codes.
- **QR Code Images**: When you scan QR codes using our extension, we process the image data to decode the QR code content.
- **Extension Usage Data**: Basic usage statistics may be collected to improve the extension's functionality.

### 2.3 Technical Information
- **Browser Information**: Basic browser and extension version information for compatibility and updates.
- **Device Information**: General device information necessary for extension functionality.

## 3. How We Use Your Information

### 3.1 Primary Functions
- **QR Code Generation**: Process URLs to create QR codes with your chosen customization settings.
- **QR Code Scanning**: Decode QR code images to extract and display their content.
- **History Management**: Store and manage your QR code generation and scanning history locally.
- **Customization**: Apply your preferred styling and design options to generated QR codes.

### 3.2 Improvement and Maintenance
- **Bug Fixes**: Use technical information to identify and resolve issues.
- **Feature Development**: Analyze usage patterns to improve functionality.
- **Performance Optimization**: Monitor extension performance to ensure smooth operation.

## 4. Data Storage and Security

### 4.1 Local Storage
- **Chrome Storage API**: All data is stored locally using Chrome's storage.local API.
- **No Cloud Storage**: We do not upload or store your data on external servers.
- **Automatic Cleanup**: QR code history is limited to 50 items and older entries are automatically removed.

### 4.2 Data Security
- **Local Processing**: All QR code generation and scanning occurs locally on your device.
- **No External Transmission**: URLs and QR code content are not sent to external servers.
- **Secure Permissions**: We only request necessary permissions for core functionality.

## 5. Data Sharing and Third Parties

### 5.1 No Data Sharing
We do not sell, trade, or otherwise transfer your personal information to third parties.

### 5.2 Third-Party Services
- **Google Fonts**: We may load fonts from Google Fonts for UI display purposes.
- **No Analytics**: We do not use third-party analytics services that collect personal data.

### 5.3 Legal Requirements
We may disclose information if required by law or to protect our rights and safety.

## 6. Your Rights and Choices

### 6.1 Access and Control
- **View History**: You can view and manage your QR code history through the extension interface.
- **Delete Data**: You can delete individual history items or clear all history data.
- **Disable Extension**: You can disable or uninstall the extension at any time.

### 6.2 Data Retention
- **Local Storage**: Data is retained only as long as the extension is installed and used.
- **Uninstall**: All local data is automatically deleted when you uninstall the extension.

## 7. Permissions We Request

### 7.1 Required Permissions
- **activeTab**: To access the URL of your current tab for QR code generation.
- **downloads**: To allow you to download generated QR codes as images.
- **clipboardWrite**: To copy QR code content to your clipboard.
- **storage**: To save your preferences and QR code history locally.
- **tabs**: To access tab information for QR code generation.
- **contextMenus**: To provide right-click menu options for QR code scanning.
- **scripting**: To inject necessary scripts for QR code scanning functionality.

### 7.2 Host Permissions
- **http://*/* and https://*/***: To access web pages for QR code generation and scanning.

## 8. Children's Privacy

Our extension is not intended for use by children under 13 years of age. We do not knowingly collect personal information from children under 13.

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify users of any material changes by:
- Updating the "Last Updated" date at the top of this policy
- Posting the updated policy in the extension
- Requiring users to accept the new policy before continuing to use the extension

## 10. Contact Information

If you have any questions about this Privacy Policy or our data practices, please contact us at:
- Email: ertal266@gmail.com

## 11. Data Processing Details

### 11.1 QR Code Generation Process
1. Extension captures the URL of your active browser tab
2. URL is validated and sanitized to remove potentially harmful content
3. QR code is generated locally using the sanitized URL
4. Generated QR code is displayed and can be downloaded or saved to history

### 11.2 QR Code Scanning Process
1. Extension processes QR code images when you right-click on them
2. Image data is analyzed locally using the jsQR library
3. Decoded content is sanitized to remove potentially harmful scripts
4. Safe content is displayed and can be copied to clipboard or saved to history

### 11.3 Data Sanitization
- URLs are validated to ensure they use safe protocols (http, https, data, blob)
- Script tags and potentially harmful content are removed from decoded data
- All user inputs are sanitized before processing

## 12. Compliance

This extension is designed to comply with:
- Chrome Web Store Developer Program Policies
- General Data Protection Regulation (GDPR) principles
- California Consumer Privacy Act (CCPA) requirements
- Other applicable privacy laws and regulations

---

**Note:** This privacy policy applies specifically to the SnapQraft Chrome extension. By using this extension, you acknowledge that you have read and understood this privacy policy and agree to its terms.
